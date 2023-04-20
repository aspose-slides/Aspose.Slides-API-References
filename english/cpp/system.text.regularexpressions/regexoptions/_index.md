---
title: RegexOptions
second_title: Aspose.Slides for C++ API Reference
description: Regex options.
type: docs
weight: 105
url: /cpp/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum


[Regex](../regex/) options.

```cpp
enum class RegexOptions
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 | Default behavior. |
| Compiled | 1 | Compile regex for performance. Always done by default. |
| CultureInvariant | 2 | Use culture-invariant matching. Ignored. |
| ECMAScript | 4 | Use ECMAScript syntax. Ignored. |
| ExplicitCapture | 8 | Explicit capturing only. Ignored. |
| IgnoreCase | 16 | Ignore case when matching. |
| IgnorePatternWhitespace | 32 | Ignore whitespaces in pattern. Unsupported. |
| Multiline | 64 | Treat '^' and '$' as beginning and end of line, not whole string. |
| RightToLeft | 128 | Right-to-left matching. Unsupported. |
| Singleline | 256 | Makes '.' match any character without exceptions (normally, newline characters are not matched). |

## See Also

* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.Slides](../../)