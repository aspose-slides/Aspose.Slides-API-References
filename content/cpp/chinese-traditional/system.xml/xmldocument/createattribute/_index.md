---
title: CreateAttribute()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的名稱建立 XmlAttribute。
type: docs
weight: 274
url: /zh-hant/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) method


建立具有指定名稱的[XmlAttribute](../../xmlattribute/)。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 屬性的限定名稱。如果名稱包含冒號，[XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值會反映冒號前的部分，而 [XmlDocument::get_LocalName](../get_localname/) 值會反映冒號後的部分。除非前置詞是已識別的內建前置詞（例如 **xmlns**），否則 [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) 會保持為空。在此情況下 get_NamespaceURI 的值為 [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/)。 |

### 傳回值

新的[XmlAttribute](../../xmlattribute/)。

## XmlDocument::CreateAttribute(const String\&, const String\&) method


建立具有指定限定名稱與[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)的[XmlAttribute](../../xmlattribute/)。

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 屬性的限定名稱。如果名稱包含冒號，則 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值會反映冒號前的部分，而 [XmlDocument::get_LocalName](../get_localname/) 值會反映冒號後的部分。 |
| namespaceURI | const [String](../../../system/string/)\& | 屬性的 namespaceURI。若限定名稱包含 **xmlns** 前置詞，則此參數必須為 [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/)。 |

### 傳回值

新的[XmlAttribute](../../xmlattribute/)。

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) method


建立具有指定[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](../get_localname/)和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)的[XmlAttribute](../../xmlattribute/)。

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 屬性的前置詞（如果有）。[String::Empty](../../../system/string/empty/) 與 **nullptr** 等價。 |
| localName | const [String](../../../system/string/)\& | 屬性的本地名稱。 |
| namespaceURI | const [String](../../../system/string/)\& | 屬性的 namespace URI（如果有）。[String::Empty](../../../system/string/empty/) 與 **nullptr** 等價。如果 **prefix** 為 **xmlns**，則此參數必須為 [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;)，否則會拋出例外。 |

### 傳回值

新的[XmlAttribute](../../xmlattribute/)。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlAttribute](../../xmlattribute/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)