---
title: HasAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün belirtilen ada sahip bir özniteliği olup olmadığını belirler.
type: docs
weight: 300
url: /tr/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) yöntemi

Geçerli düğümün belirtilen ada sahip bir özniteliği olup olmadığını belirler.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Bulunacak özniteliğin adı. Bu, nitelikli bir isimdir. Eşleşen düğümün **get_Name** değeriyle karşılaştırılır. |

### Dönüş Değeri

Geçerli düğüm belirtilen özniteliğe sahipse **true**; aksi takdirde **false**.

## XmlElement::HasAttribute(String, String) yöntemi

Geçerli düğümün belirtilen yerel ada ve ad alanı URI'sine sahip bir özniteliği olup olmadığını belirler.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Bulunacak özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Bulunacak özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Geçerli düğüm belirtilen özniteliğe sahipse **true**; aksi takdirde **false**.

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [XmlElement](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)