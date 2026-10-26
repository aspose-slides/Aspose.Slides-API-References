---
title: ReadContentAs()
second_title: Aspose.Slides için C++ API Referansı
description: İçeriği belirtilen türde bir nesne olarak okur.
type: docs
weight: 456
url: /tr/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodu

İçeriği belirtilen türde bir nesne olarak okur.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Dönülecek değerin tipi. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Tür dönüşümüyle ilgili olası isim uzayı öneklerini çözmek için kullanılan bir [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) nesnesi. Örneğin, bu bir [XmlQualifiedName](../../xmlqualifiedname/) nesnesini **xs:string** tipine dönüştürürken kullanılabilir. Bu değer **nullptr** olabilir. |

### Dönüş Değeri

İstenen tipe dönüştürülmüş birleştirilmiş metin içeriği veya öznitelik değeri.

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Sınıf [XmlReader](../)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)