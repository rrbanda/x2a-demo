# X2A Demo - Chef to Ansible Migration

This repository contains a sample Chef cookbook used to demonstrate
[X2A Convertor](https://github.com/x2ansible/x2a-convertor) -- an AI-powered
tool that migrates Chef, Puppet, and Salt configurations to Ansible.

## Repository Structure

```
hello_world/          # Chef cookbook to be migrated
  recipes/
    default.rb        # Main recipe - logs "Hello, World!"
  metadata.rb         # Cookbook metadata (name, version, maintainer)
  metadata.json       # Cookbook metadata in JSON format
```

## Usage with X2A

1. Open the X2A page in Red Hat Developer Hub
2. Create a new conversion project pointing to this repository
3. Run the migration phases: **Init** -> **Analyze** -> **Migrate** -> **Publish**
4. Review the generated Ansible role in the target branch

## Original Cookbook

The `hello_world` cookbook is a minimal Chef cookbook from
[Chef Supermarket](https://supermarket.chef.io/cookbooks/hello_world)
that logs a "Hello, World!" message during a Chef run.
