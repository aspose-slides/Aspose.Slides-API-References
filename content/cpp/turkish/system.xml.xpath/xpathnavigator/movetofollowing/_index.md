---
title: MoveToFollowing()
second_title: Aspose.Slides için C++ API Referansı
description: XPathNavigator'ı belge sırasına göre belirtilen yerel ad ve ad alanı URI'sına sahip öğeye taşır.
type: docs
weight: 703
url: /tr/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) yöntemi

[XPathNavigator](../) öğesini, belge sırasına göre yerel adı ve ad alanı URI'sı belirtilen öğeye taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öğenin ad alanı URI'sı. |

### Dönüş Değeri

**true**, [XPathNavigator](../) başarıyla taşındıysa; aksi takdirde **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) yöntemi

[XPathNavigator](../) öğesini, belge sırasına göre yerel adı ve ad alanı URI'sı belirtilen öğeye, belirtilen sınıra kadar taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öğenin ad alanı URI'sı. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Takip eden öğeyi ararken mevcut [XPathNavigator](../)'nin geçmeyeceği öğe sınırında konumlandırılmış [XPathNavigator](../) nesnesi. |

### Dönüş Değeri

**true**, [XPathNavigator](../) başarıyla taşındıysa; aksi takdirde **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) yöntemi

[XPathNavigator](../) öğesini, belge sırasına göre belirtilen XPathNodeType'ın sonraki öğesine taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Öğenin XPathNodeType'ı. XPathNodeType [XPathNodeType::Attribute](../../xpathnodetype/) veya [XPathNodeType::Namespace](../../xpathnodetype/) olamaz. |

### Dönüş Değeri

**true**, [XPathNavigator](../) başarıyla taşındıysa; aksi takdirde **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) yöntemi

[XPathNavigator](../) öğesini, belge sırasına göre belirtilen XPathNodeType'ın sonraki öğesine, belirtilen sınıra kadar taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Öğenin XPathNodeType'ı. XPathNodeType [XPathNodeType::Attribute](../../xpathnodetype/) veya [XPathNodeType::Namespace](../../xpathnodetype/) olamaz. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Takip eden öğeyi ararken mevcut [XPathNavigator](../)'nin geçmeyeceği öğe sınırında konumlandırılmış [XPathNavigator](../) nesnesi. |

### Dönüş Değeri

**true**, [XPathNavigator](../) başarıyla taşındıysa; aksi takdirde **false**.

## Ayrıca Bakınız

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)