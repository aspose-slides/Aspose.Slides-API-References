---
title: HexUnescape()
second_title: Aspose.Slides C++ API 参考
description: 将指定字符的十六进制表示转换为字符。
type: docs
weight: 443
url: /zh/system/uri/hexunescape/
---
## Uri::HexUnescape(const String\&, int32_t\&) 方法


将指定字符的十六进制表示转换为字符。

```cpp
static char16_t System::Uri::HexUnescape(const String &pattern, int32_t &index)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pattern | const [String](../../string/)\& | 包含字符十六进制表示的字符串 |
| index | **int32_t**\& | **pattern** 中字符十六进制表示开始的位置 |

### 返回值

位于 **index** 位置的十六进制编码所表示的字符。如果 **index** 处的字符未进行十六进制编码，则返回 **index** 处的字符。**index** 的值会递增，指向返回的字符之后的字符。

## 另请参见

* 类 [String](../../string/)
* 类 [Uri](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)