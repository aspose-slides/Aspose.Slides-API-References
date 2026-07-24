---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen URL'deki XML Şema tanım dili (XSD) şemasını XmlSchemaSet'e ekler.
type: docs
weight: 157
url: /tr/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) metod


Belirtilen URL'deki XML [Schema](../../) tanım dili (XSD) şemasını [XmlSchemaSet](../)'ye ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Şemanın **targetNamespace** değeri veya şemada belirtilen **targetNamespace**'i kullanmak için **nullptr**. |
| schemaUri | const [String](../../../system/string/)\& | Yüklenmesi gereken şemayı belirten URL. |

### Dönüş Değeri

Geçerli ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değil ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde bir XmlSchemaException fırlatılır.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) metod


XML [Schema](../../) tanım dili (XSD) şemasını [XmlReader](../../../system.xml/xmlreader/) içinde bulunan [XmlSchemaSet](../)'ye ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Şemanın **targetNamespace** değeri veya şemada belirtilen **targetNamespace**'i kullanmak için **nullptr**. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

### Dönüş Değeri

Geçerli ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değil ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde bir XmlSchemaException fırlatılır.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) metod


Verilen [XmlSchemaSet](../) içindeki tüm XML [Schema](../../) tanım dili (XSD) şemalarını [XmlSchemaSet](../)'ye ekler.

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | [XmlSchemaSet](../) nesnesi. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) metod


Verilen [XmlSchema](../../xmlschema/)'yi [XmlSchemaSet](../)'ye ekler.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchemaSet](../)'e eklemek için [XmlSchema](../../xmlschema/) nesnesi. |

### Dönüş Değeri

Geçerli ise bir [XmlSchema](../../xmlschema/) nesnesi. Şema geçerli değil ve bir ValidationEventHandler belirtilmişse, **nullptr** döndürülür ve uygun doğrulama olayı tetiklenir. Aksi takdirde bir XmlSchemaException fırlatılır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlSchema](../../xmlschema/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlSchemaSet](../)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Ad alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)