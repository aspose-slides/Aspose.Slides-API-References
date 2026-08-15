---
title: CreateElement()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 建立具有指定名稱的元素。
type: docs
weight: 339
url: /zh-hant/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) 方法

建立具有指定名稱的元素。

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 元素的合格名稱。若名稱包含冒號，則 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值會反映冒號前的部分，而 [XmlDocument::get_LocalName](../get_localname/) 值會反映冒號後的部分。合格名稱不得包含 **xmlns** 前綴。 |

### 傳回值

新的 [XmlElement](../../xmlelement/)。

## XmlDocument::CreateElement(const String\&, const String\&) 方法

使用合格名稱與[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)建立[XmlElement](../../xmlelement/)。

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | 元素的合格名稱。若名稱包含冒號，則 [XmlNode::get_Prefix](../../xmlnode/get_prefix/) 值會反映冒號前的部分，而 [XmlDocument::get_LocalName](../get_localname/) 值會反映冒號後的部分。合格名稱不得包含 **xmlns** 前綴。 |
| namespaceURI | const [String](../../../system/string/)\& | 元素的命名空間 URI。 |

### 傳回值

新的 [XmlElement](../../xmlelement/)。

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) 方法

建立具有指定[XmlNode::get_Prefix](../../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](../get_localname/)和[XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)的元素。

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 新元素的前綴（如果有）。[String::Empty](../../../system/string/empty/) 與 **nullptr** 等價。 |
| localName | const [String](../../../system/string/)\& | 新元素的本機名稱。 |
| namespaceURI | const [String](../../../system/string/)\& | 新元素的命名空間 URI（如果有）。[String::Empty](../../../system/string/empty/) 與 **nullptr** 等價。 |

### 傳回值

新的 [XmlElement](../../xmlelement/)。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlElement](../../xmlelement/)
* 類別 [String](../../../system/string/)
* 類別 [XmlDocument](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)