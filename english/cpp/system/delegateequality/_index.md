---
title: DelegateEquality
second_title: Aspose.Slides for C++ API Reference
description: "Result of delegate equality comparison. In C++, it is forbidden to directly compare instances of std::function for equality, so at some cases the only thing possible is to say whether some delegates are alike or not."
type: docs
weight: 2679
url: /cpp/system/delegateequality/
---
## DelegateEquality enum


Result of delegate equality comparison. In C++, it is forbidden to directly compare instances of std::function for equality, so at some cases the only thing possible is to say whether some delegates are alike or not.

```cpp
enum class DelegateEquality
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Equals | 0 | Delegates are guaranteed to be the same. |
| Alike | 1 | Delegates can be the same, but precise comparison is impossible. |
| None | 2 | Delegates are guaranteed to be different. |

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
