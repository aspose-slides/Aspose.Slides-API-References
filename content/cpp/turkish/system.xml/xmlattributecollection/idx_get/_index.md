---
title: idx_get()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen indeksteki özniteliği döndürür.
type: docs
weight: 1
url: /tr/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) metodu


Belirtilen indeksteki özniteliği döndürür.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Özniteliğin indeksi. |

### Dönüş Değeri

Belirtilen indeksteki öznitelik.

## XmlAttributeCollection::idx_get(const String\&) metodu


Belirtilen adla özniteliği döndürür.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Özniteliğin nitelikli adı. |

### Dönüş Değeri

Belirtilen ada sahip öznitelik. Öznitelik mevcut değilse, bu yöntem **nullptr** döndürür.

## XmlAttributeCollection::idx_get(const String\&, const String\&) metodu


Belirtilen yerel ad ve ad uzayı Evrensel Kaynak Tanımlayıcısı (URI) ile özniteliği döndürür.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Özniteliğin yerel adı. |
| namespaceURI | const [String](../../../system/string/)\& | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen yerel ad ve ad alanı URI'sine sahip öznitelik. Öznitelik mevcut değilse, bu yöntem **nullptr** döndürür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)