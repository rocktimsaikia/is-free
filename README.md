# isfree

Check if a domain is available using DNS.

## Installation

```bash
pip install isfree
```

## Usage

```bash
isfree example.com
```

Output:

```
✓ example.com is available
✗ google.com is taken
⚠ Invalid TLD: .invalidtld
```

Exit codes: `0` (available), `1` (taken), `2` (error)
