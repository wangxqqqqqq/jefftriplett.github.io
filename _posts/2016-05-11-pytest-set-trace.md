---
layout: post
title: "Use `pytest.set_trace` to set a breakpoint in py.test"
date: 2016-05-11
category: TIL
location: Lawrence, Kansas United States
tags:
 - python
 - pytest
 - py.test
 - pdb
---

To set a breakpoint in py.test, use:

```python
import pytest

pytest.set_trace()
```

[source](https://docs.pytest.org/en/latest/usage.html?highlight=breakpoint#setting-a-breakpoint-aka-set-trace)
