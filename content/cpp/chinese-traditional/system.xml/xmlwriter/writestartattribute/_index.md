---
title: WriteStartAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 寫入屬性的開始，使用指定的本機名稱和命名空間 URI。
type: docs
weight: 144
url: /zh-hant/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) 方法

寫入屬性的開始，使用指定的本機名稱和命名空間 URI。

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 屬性的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 屬性的命名空間 URI。 |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) 方法

在派生類別中覆寫時，寫入屬性的開始，使用指定的前置詞、本機名稱和命名空間 URI。

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 屬性的命名空間前置詞。 |
| localName | const [String](../../../system/string/)\& | 屬性的本機名稱。 |
| ns | const [String](../../../system/string/)\& | 屬性的命名空間 URI。 |

## XmlWriter::WriteStartAttribute(const String\&) 方法

寫入屬性的開始，使用指定的本機名稱。

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 屬性的本機名稱。 |

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlWriter](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)