# datacenter

A classic data center design with core/distribution/access layer

## Topology

![Alt Text](./topology.png)


## Usage

If you are using [virlutils](https://github.com/kecorbin/virlutils) you can
instantiate this topology by simply typing

```
virl up virlfiles/datacenter
```

If you are launching your simulation by some other means, you will want
to download the topology.virl file, and import modify it by changing the
`{{ gateway }}` tags to reflect your current VIRL environment.
