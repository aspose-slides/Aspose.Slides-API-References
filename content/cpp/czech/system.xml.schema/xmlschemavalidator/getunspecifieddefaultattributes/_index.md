---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides pro C++ API Reference
description: "Ověřuje identitní omezení na výchozích atributech a naplňuje zadaný List objekty XmlSchemaAttribute pro všechny atributy s výchozími hodnotami, které dosud nebyly ověřeny pomocí metody XmlSchemaValidator::ValidateAttribute v kontextu prvku."
type: docs
weight: 157
url: /cs/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) metoda

Ověřuje identitní omezení na výchozích atributech a naplňuje uvedený List objekty [XmlSchemaAttribute](../../xmlschemaattribute/) pro všechny atributy s výchozími hodnotami, které dosud nebyly ověřeny pomocí metody [XmlSchemaValidator::ValidateAttribute](../validateattribute/) v kontextu prvku.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | List, který se naplní objekty [XmlSchemaAttribute](../../xmlschemaattribute/) pro všechny atributy, které dosud nebyly během ověřování v kontextu prvku zaznamenány. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [List](../../../system.collections.generic/list/)
* Třída [Object](../../../system/object/)
* Třída [XmlSchemaValidator](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)