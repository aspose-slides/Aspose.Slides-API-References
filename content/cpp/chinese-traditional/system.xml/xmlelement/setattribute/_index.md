---
title: SetAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 設定具有指定名稱的屬性值。
type: docs
weight: 222
url: /zh-hant/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) 方法

設定具有指定名稱的屬性值。

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 要建立或變更的屬性名稱。這是一個合格名稱。若名稱包含冒號，則會被解析為前置詞與本地名稱部分。 |
| value | [String](../../../system/string/) | 要設定給屬性的值。 |

## XmlElement::SetAttribute(String, String, String) 方法

設定具有指定本地名稱與命名空間 URI 的屬性值。

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 屬性的本地名稱。 |
| namespaceURI | [String](../../../system/string/) | 屬性的命名空間 URI。 |
| value | [String](../../../system/string/) | 要設定給屬性的值。 |

### 傳回值

屬性值。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlElement](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)