# ripe-lg-graph

A somewhat hacky way to have bgpmap data from RIPE NCC's RIS. Does not take count the prepends.

**Requires >=python3.7.**

## Dependencies

  - dnspython
  - pydot _(external dependency: dot)_
  - requests

Other than the external dependency, you can do `python3 -m pip install -r requirements.txt`

## Usage

```
python3 ripe-lg-graph.py <ip or prefix>
```

For example:

```
python3 ripe-lg-graph.py 2606:4700:4700::1111
```

Or:

```
python3 ripe-lg-graph.py 2606:4700:4700::/48
```

## Example output

![Cloudflare DNS](https://btw.i-use-ar.ch/i/zfvlw996.svg)
