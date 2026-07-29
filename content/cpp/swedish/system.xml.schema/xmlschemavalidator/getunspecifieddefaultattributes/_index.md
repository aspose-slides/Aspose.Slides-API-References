---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides för C++ API-referens
description: "Validerar identitetsrestriktioner på standardattributen och fyller den specificerade List med XmlSchemaAttribute-objekt för alla attribut med standardvärden som ännu inte har validerats med XmlSchemaValidator::ValidateAttribute-metoden i elementkontext."
type: docs
weight: 157
url: /sv/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) metod


Validerar identitetsrestriktioner på standardattributen och fyller den specificerade List med [XmlSchemaAttribute](../../xmlschemaattribute/)-objekt för alla attribut med standardvärden som ännu inte har validerats med [XmlSchemaValidator::ValidateAttribute](../validateattribute/) metod i elementkontext.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | En List att fylla med [XmlSchemaAttribute](../../xmlschemaattribute/)-objekt för alla attribut som ännu inte har påträffats under validering i elementkontext. |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [List](../../../system.collections.generic/list/)
* Klass [Object](../../../system/object/)
* Klass [XmlSchemaValidator](../)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)