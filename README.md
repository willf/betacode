# Betacode

A Python library for converting between Greek text and Beta Code.

## Installation

```bash
pip install betacode
```

## Usage

```python
import betacode

betacode.to_unicode('mh=nin') # 'μῆνιν'

betacode.to_betacode('μῆνιν') # 'mh=nin'

```
