# Architector Wheels

Precompiled Python wheels for architector deployment.

## Wheels (Python 3.13, Linux x86_64)

| Package | Version | Size | Description |
|---------|---------|------|-------------|
| pynauty | 2.8.8.1 | 171KB | Graph isomorphism library |
| xtb | 22.1 | 60MB | Tight-binding calculations (bundled shared libs) |

## Usage in MLflow pip_requirements

```python
pip_requirements = [
    "pynauty @ https://github.com/runtian97/architector-wheels/releases/download/v1.0/pynauty-2.8.8.1-cp313-cp313-linux_x86_64.whl",
    "xtb @ https://github.com/runtian97/architector-wheels/releases/download/v1.0/xtb-22.1-cp313-cp313-linux_x86_64.whl",
    "architector==0.0.10",
]
```

