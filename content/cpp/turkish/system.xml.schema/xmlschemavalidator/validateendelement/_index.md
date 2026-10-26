---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API Referansı
description: Basit içerikli öğeler için öğenin metin içeriğinin veri tipine göre geçerli olup olmadığını doğrular ve karmaşık içerikli öğeler için mevcut öğenin içeriğinin tamamlanmış olup olmadığını doğrular.
type: docs
weight: 209
url: /tr/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method

Basit içeriğe sahip öğeler için öğenin metin içeriğinin veri türüne göre geçerli olup olmadığını doğrular ve karmaşık içeriğe sahip öğeler için geçerli öğenin içeriğinin tamamlanmış olup olmadığını doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) nesnesi, öğenin başarılı doğrulamasının ardından özellikleri ayarlanır. Bu parametre **nullptr** olabilir. |

### Dönüş Değeri

Öğenin basit içeriğe sahip olması durumunda, ayrıştırılmış, tiplenmiş metin değeri.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method

Belirtilen öğenin metin içeriğinin veri türüne göre geçerli olup olmadığını doğrular.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | [XmlSchemaInfo](../../xmlschemainfo/) nesnesi, öğenin metin içeriğinin başarılı doğrulamasının ardından özellikleri ayarlanır. Bu parametre **nullptr** olabilir. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Öğenin tiplenmiş metin içeriği. |

### Dönüş Değeri

Öğenin ayrıştırılmış, tiplenmiş basit içeriği.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)