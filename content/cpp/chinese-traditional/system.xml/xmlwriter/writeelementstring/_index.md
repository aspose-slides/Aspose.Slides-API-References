---
title: WriteElementString()
second_title: Aspose.Slides for C++ API 參考
description: 寫入具有指定本機名稱與值的元素。
type: docs
weight: 443
url: /zh-hant/system.xml/xmlwriter/writeelementstring/
---
## XmlWriter::WriteElementString(const String\&, const String\&) 方法

寫入具有指定本機名稱與值的元素。

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &localName, const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本機名稱。 |
| value | const [String](../../../system/string/)\& | 元素的值。 |

## XmlWriter::WriteElementString(const String\&, const String\&, const String\&) 方法

寫入具有指定本機名稱、命名空間 URI 與值的元素。

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &localName, const String &ns, const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 與元素關聯的命名空間 URI。 |
| value | const [String](../../../system/string/)\& | 元素的值。 |

## XmlWriter::WriteElementString(const String\&, const String\&, const String\&, const String\&) 方法

寫入具有指定前綴、本機名稱、命名空間 URI 與值的元素。

```cpp
void System::Xml::XmlWriter::WriteElementString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 元素的前綴。 |
| localName | const [String](../../../system/string/)\& | 元素的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 元素的命名空間 URI。 |
| value | const [String](../../../system/string/)\& | 元素的值。 |

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)