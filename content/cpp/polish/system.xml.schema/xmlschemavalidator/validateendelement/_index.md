---
title: ValidateEndElement()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy zawartość tekstowa elementu jest prawidłowa zgodnie z jego typem danych dla elementów z prostą zawartością, oraz sprawdza, czy zawartość bieżącego elementu jest kompletna dla elementów ze złożoną zawartością.
type: docs
weight: 209
url: /pl/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) metoda

Sprawdza, czy zawartość tekstowa elementu jest prawidłowa zgodnie z jego typem danych dla elementów z prostą zawartością oraz sprawdza, czy zawartość bieżącego elementu jest kompletna dla elementów z złożoną zawartością.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Obiekt [XmlSchemaInfo](../../xmlschemainfo/), którego właściwości są ustawiane po pomyślnej walidacji elementu. Ten parametr może być **nullptr**. |

### Wartość zwracana

Zanalizowana, typowana wartość tekstowa elementu, jeśli element ma prostą zawartość.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) metoda

Sprawdza, czy zawartość tekstowa określonego elementu jest prawidłowa zgodnie z jego typem danych.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Obiekt [XmlSchemaInfo](../../xmlschemainfo/), którego właściwości są ustawiane po pomyślnej walidacji zawartości tekstowej elementu. Ten parametr może być **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Typowana zawartość tekstowa elementu. |

### Wartość zwracana

Zanalizowana, typowana prosta zawartość elementu.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [XmlSchemaInfo](../../xmlschemainfo/)
* Klasa [XmlSchemaValidator](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)