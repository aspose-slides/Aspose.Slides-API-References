---
title: WriteAttributeString()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，寫入具備指定本機名稱、命名空間 URI 與值的屬性。
type: docs
weight: 131
url: /zh-hant/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) 方法

當在衍生類別中覆寫時，寫入具備指定本機名稱、命名空間 URI 與值的屬性。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 屬性的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 與屬性相關聯的命名空間 URI。 |
| value | const [String](../../../system/string/)\& | 屬性的值。 |

## XmlWriter::WriteAttributeString(const String\&, const String\&) 方法

當在衍生類別中覆寫時，寫出具備指定本機名稱與值的屬性。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 屬性的本機名稱。 |
| value | const [String](../../../system/string/)\& | 屬性的值。 |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) 方法

當在衍生類別中覆寫時，寫出具備指定前置詞、本機名稱、命名空間 URI 與值的屬性。

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 屬性的命名空間前置詞。 |
| localName | const [String](../../../system/string/)\& | 屬性的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 屬性的命名空間 URI。 |
| value | const [String](../../../system/string/)\& | 屬性的值。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)