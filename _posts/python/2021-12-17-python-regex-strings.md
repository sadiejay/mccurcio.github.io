---
title: "Python - Regex for Strings"
tags: Python Regex
---

Convert repeated spaces to one space: 

- The snippet below clears out the repeated spaces in a text and replaces it with single space. 

- `re` is a regular expression module to find more than one occurrences of space with ‘[ ]+’.

```
import re
re.sub(r"[ ]+", ' ', 'this    sentence          has              non-uniform      spaces')
```
