---
title: get_SchemaInfo()
second_title: C++ için Aspose.Slides API Referansı
description: Şema doğrulaması sonucu geçerli düğüme atanmış şema bilgisini döndürür.
type: docs
weight: 196
url: /tr/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() metodu


Şema doğrulaması sonucunda geçerli düğüme atanan şema bilgisini döndürür.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```


### Dönüş Değeri

Geçerli düğüm için şema bilgisini içeren bir IXmlSchemaInfo nesnesi. [Schema](../../../system.xml.schema/) bilgisi öğelere, özniteliklere veya null olmayan [XmlReader::get_ValueType](../get_valuetype/) değerine sahip metin düğümlerine ayarlanabilir. Geçerli düğüm yukarıdaki düğüm türlerinden biri değilse veya [XmlReader](../) örneği şema bilgisini raporlamıyorsa, bu metot **nullptr** döndürür. Bu metot bir [XmlTextReader](../../xmltextreader/) veya bir [XmlValidatingReader](../../xmlvalidatingreader/) nesnesinden çağrılırsa, metod her zaman **nullptr** döndürür. Bu [XmlReader](../) uygulamaları şema bilgisini get_SchemaInfo metodu aracılığıyla ortaya çıkarmaz.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)