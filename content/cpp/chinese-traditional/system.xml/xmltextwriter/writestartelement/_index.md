---
title: WriteStartElement()
second_title: Aspose.Slides C++ API 參考
description: 寫入指定的起始標記，並將其與給定的命名空間和前置字首關聯。
type: docs
weight: 235
url: /zh-hant/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String&, const String&, const String&) 方法


寫入指定的起始標記，並將其與給定的命名空間和前置字首關聯。

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 元素的命名空間前置字首。 |
| localName | const [String](../../../system/string/)\& | 元素的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 與元素關聯的命名空間 URI。若此命名空間已在範圍內且已有關聯的前置字首，則寫入器會自動寫入該前置字首。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlTextWriter](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)