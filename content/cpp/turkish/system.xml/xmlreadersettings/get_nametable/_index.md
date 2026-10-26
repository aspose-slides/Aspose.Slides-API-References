---
title: get_NameTable()
second_title: Aspose.Slides for C++ API Referansı
description: Atomize edilmiş dize karşılaştırmaları için kullanılan XmlNameTable'ı döndürür.
type: docs
weight: 1
url: /tr/system.xml/xmlreadersettings/get_nametable/
---
## XmlReaderSettings::get_NameTable() metot


Atomize edilmiş dize karşılaştırmaları için kullanılan [XmlNameTable](../../xmlnametable/) değerini döndürür.

```cpp
SharedPtr<XmlNameTable> System::Xml::XmlReaderSettings::get_NameTable()
```


### Dönüş Değeri

[XmlNameTable](../../xmlnametable/) tüm [XmlReader](../../xmlreader/) örnekleri tarafından kullanılan atomize edilmiş dizeleri depolar ve bu [XmlReaderSettings](../) nesnesi kullanılarak oluşturulan örnekler için geçerlidir. Varsayılan değer **nullptr**'dır. Oluşturulan [XmlReader](../../xmlreader/) örneği, bu değer **nullptr** ise yeni boş bir [NameTable](../../nametable/) kullanacaktır.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNameTable](../../xmlnametable/)
* Sınıf [XmlReaderSettings](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)