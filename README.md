# jRAT Controller API

API for developing controller-side plugins for jRAT

## How to start using it

You need to add it to your classpath. You do not need to include the API in the plugin, jRAT will already have it loaded.

## Requirements

- [pluginlib](https://github.com/redpois0n/pluginlib)

## Structure

Both your Controller and Stub plugin need a plugin.txt file in the root that will contain the main class name (like se.jrat.MainClass)

## System Properties

You can get current jRAT version by accessing property jrat.version and current directory jrat.dir (same as user.dir)