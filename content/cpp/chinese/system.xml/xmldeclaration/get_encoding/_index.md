---
title: get_Encoding()
second_title: Aspose.Slides for C++ API 参考
description: 返回 XML 文档的编码级别。
type: docs
weight: 14
url: /zh/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() 方法

返回 XML 文档的编码级别。

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### 返回值

有效的字符编码名称。

## 备注

XML 最常支持的字符编码名称如下：

| 类别 | 编码名称 |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

此值是可选的。如果未设置值，此方法返回 [String::Empty](../../../system/string/empty/)。如果未包含 encoding 属性，则在写入或保存文档时默认使用 UTF-8 编码。

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlDeclaration](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)