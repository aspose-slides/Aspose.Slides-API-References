---
title: WriteStartElement()
second_title: Aspose.Slides for C++ API 參考
description: 當在衍生類別中覆寫時，寫入指定的起始標籤並將其與給定的名稱空間關聯。
type: docs
weight: 92
url: /zh-hant/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) 方法

當在衍生類別中覆寫時，寫入指定的起始標籤並將其與給定的名稱空間關聯。

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本地名稱。 |
| ns | const [String](../../../system/string/)\& | 與元素關聯的名稱空間 URI。若此名稱空間已在範圍內且具有關聯的前置詞，寫入器會自動寫入該前置詞。 |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) 方法

當在衍生類別中覆寫時，寫入指定的起始標籤並將其與給定的名稱空間及前置詞關聯。

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 元素的名稱空間前置詞。 |
| localName | const [String](../../../system/string/)\& | 元素的本地名稱。 |
| ns | const [String](../../../system/string/)\& | 與元素關聯的名稱空間 URI。 |

## XmlWriter::WriteStartElement(const String\&) 方法

當在衍生類別中覆寫時，寫出具指定本地名稱的起始標籤。

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 元素的本地名稱。 |

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)