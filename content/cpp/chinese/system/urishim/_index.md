---
title: UriShim
second_title: Aspose.Slides for C++ API 参考
description: 服务类。
type: docs
weight: 1405
url: /zh/system/urishim/
---
## UriShim 类

服务类。

```cpp
class UriShim
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [EscapeAsciiChar](./escapeasciichar/)(char16_t, const [System::ArrayPtr](../arrayptr/)\<char16_t\>\&, **int32_t**\&) | 将字符转换为转义的十六进制形式。 |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | 将字符转换为转义的十六进制形式。 |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | 将字符从转义的十六进制形式转换。 |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | 检查给定的模式是否为转义的十六进制形式。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)