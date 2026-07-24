---
title: RemoveAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Bir özniteliği ad ile kaldırır.
type: docs
weight: 235
url: /tr/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) metot


Bir özniteliği ad ile kaldırır.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kaldırılacak öznitelik adı. Bu, nitelikli bir addır. Eşleşen düğümün **get_Name** değeriyle karşılaştırılır. |

## XmlElement::RemoveAttribute(String, String) metot


Belirtilen yerel ad ve ad alanı URI'sine sahip bir özniteliği kaldırır. (Kaldırılan öznitelik varsayılan bir değere sahipse, hemen yerine konur).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Kaldırılacak öznitelik yerel adı. |
| namespaceURI | [String](../../../system/string/) | Kaldırılacak özniteliğin ad alanı URI'si. |

## See Also

* Sınıf [String](../../../system/string/)
* Sınıf [XmlElement](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)