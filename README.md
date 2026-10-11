# slugify

Transliterates and normalises text into slugs suitable for URLs and filenames.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install slugify
```

## Usage

```python
from slugify import slugify

result = slugify("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
