---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Weryfikuje ograniczenia tożsamości na domyślnych atrybutach i wypełnia podaną List obiektami XmlSchemaAttribute dla wszystkich atrybutów z wartościami domyślnymi, które nie zostały wcześniej zwalidowane przy użyciu metody XmlSchemaValidator::ValidateAttribute w kontekście elementu."
type: docs
weight: 157
url: /pl/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) metoda

Waliduje ograniczenia tożsamości na domyślnych atrybutach i wypełnia podaną List obiektami [XmlSchemaAttribute](../../xmlschemaattribute/) dla wszystkich atrybutów z domyślnymi wartościami, które nie zostały wcześniej zwalidowane przy użyciu metody [XmlSchemaValidator::ValidateAttribute](../validateattribute/) w kontekście elementu.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Lista, którą należy wypełnić [XmlSchemaAttribute](../../xmlschemaattribute/) obiektami dla wszelkich atrybutów, które nie zostały jeszcze napotkane podczas walidacji w kontekście elementu. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [List](../../../system.collections.generic/list/)
* Klasa [Object](../../../system/object/)
* Klasa [XmlSchemaValidator](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)