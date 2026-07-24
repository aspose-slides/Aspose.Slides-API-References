---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API Referansı
description: "Varsayılan öznitelikler üzerindeki kimlik kısıtlamalarını doğrular ve öğe bağlamında XmlSchemaValidator::ValidateAttribute yöntemi kullanılarak daha önce doğrulanmamış varsayılan değere sahip öznitelikler için belirtilen Listeyi XmlSchemaAttribute nesneleriyle doldurur."
type: docs
weight: 157
url: /tr/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) yöntemi

Varsayılan özniteliklerde kimlik kısıtlamalarını doğrular ve öğe bağlamında daha önce [XmlSchemaValidator::ValidateAttribute](../validateattribute/) yöntemiyle doğrulanmamış varsayılan değerleri olan öznitelikler için [XmlSchemaAttribute](../../xmlschemaattribute/) nesneleriyle belirtilen List'i doldurur.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Doğrulama sırasında öğe bağlamında henüz karşılaşılmamış öznitelikler için [XmlSchemaAttribute](../../xmlschemaattribute/) nesneleriyle doldurulacak bir List. |

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [List](../../../system.collections.generic/list/)
* Sınıf [Object](../../../system/object/)
* Sınıf [XmlSchemaValidator](../)
* Ad alanı [System::Xml::Schema](../../)
* Kütüphane [Aspose.Slides](../../../)