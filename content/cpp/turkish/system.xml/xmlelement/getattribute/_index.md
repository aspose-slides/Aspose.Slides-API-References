---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ada sahip öznitelik için değeri döndürür.
type: docs
weight: 209
url: /tr/system.xml/xmlelement/getattribute/
---
## XmlElement::GetAttribute(String) yöntemi


Belirtilen ada sahip öznitelik için değeri döndürür.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Alınacak öznitelik adı. Bu, nitelikli bir addır. Eşleşen düğümün **get_Name** değeriyle karşılaştırılır. |

### Dönüş Değeri

Belirtilen öznitelik değeri. Eşleşen bir öznitelik bulunamazsa veya öznitelik belirli bir ya da varsayılan değere sahip değilse boş bir dize döndürülür.

## XmlElement::GetAttribute(String, String) yöntemi


Belirtilen yerel ad ve ad alanı URI'sine sahip öznitelik için değeri döndürür.

```cpp
virtual String System::Xml::XmlElement::GetAttribute(String localName, String namespaceURI)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Alınacak öznitelik için yerel ad. |
| namespaceURI | [String](../../../system/string/) | Alınacak öznitelik için ad alanı URI'si. |

### Dönüş Değeri

Belirtilen öznitelik değeri. Eşleşen bir öznitelik bulunamazsa veya öznitelik belirli bir ya da varsayılan değere sahip değilse boş bir dize döndürülür.

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [XmlElement](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)