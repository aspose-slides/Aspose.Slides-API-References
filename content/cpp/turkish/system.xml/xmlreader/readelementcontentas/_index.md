---
title: ReadElementContentAs()
second_title: Aspose.Slides for C++ API Referansı
description: Öğenin içeriğini istenen türde okur.
type: docs
weight: 586
url: /tr/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metot

İstenen tür olarak öğe içeriğini okur.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Döndürülecek değerin türü. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Tür dönüşümüyle ilgili herhangi bir ad alanı önekini çözmek için kullanılan bir [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) nesnesi. |

### Dönüş Değeri

İstenen tipte nesneye dönüştürülmüş öğe içeriği.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metot

Belirtilen yerel ad ve ad alanı URIʼsinin geçerli öğe ile eşleştiğini kontrol eder, ardından öğe içeriğini istenen tür olarak okur.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Döndürülecek değerin türü. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Tür dönüşümüyle ilgili herhangi bir ad alanı önekini çözmek için kullanılan bir [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) nesnesi. |
| localName | [String](../../../system/string/) | Öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öğenin ad alanı URIʼsi. |

### Dönüş Değeri

İstenen tipte nesneye dönüştürülmüş öğe içeriği.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [TypeInfo](../../../system/typeinfo/)
* Sınıf [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Sınıf [XmlReader](../)
* Sınıf [String](../../../system/string/)
* İsim alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)