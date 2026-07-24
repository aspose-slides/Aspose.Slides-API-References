---
title: ReadElementContentAsObject()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli öğeyi okur ve içeriği bir Nesne olarak döndürür.
type: docs
weight: 469
url: /tr/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() yöntemi

Geçerli öğeyi okur ve içeriği bir [Object](../../../system/object/) olarak döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Dönüş Değeri

En uygun tipte kutulanmış bir nesne. [XmlReader::get_ValueType](../get_valuetype/) değeri uygun tipi belirler. İçerik bir liste tipi olarak tanımlanmışsa, bu yöntem uygun tipte kutulanmış nesnelerden oluşan bir dizi döndürür.

## XmlReader::ReadElementContentAsObject(String, String) yöntemi

Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğe ile eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Object](../../../system/object/) olarak döndürür.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öğenin ad alanı URI'si. |

### Dönüş Değeri

En uygun tipte kutulanmış bir nesne. [XmlReader::get_ValueType](../get_valuetype/) değeri uygun tipi belirler. İçerik bir liste tipi olarak tanımlanmışsa, bu yöntem uygun tipte kutulanmış nesnelerden oluşan bir dizi döndürür.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [XmlReader](../)
* Sınıf [String](../../../system/string/)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)