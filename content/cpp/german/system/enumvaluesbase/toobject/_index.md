---
title: ToObject()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert den angegebenen 64-bit vorzeichenlosen Ganzzahlwert in ein Aufzählungsmitglied.
type: docs
weight: 40
url: /de/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) Methode

Konvertiert den angegebenen 64-Bit-vorzeichenlosen Ganzzahlwert in ein Aufzählungsmitglied.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Der aufzurufende Aufzählungstyp. |
| value | **uint64_t** | Der Wert, der in ein Aufzählungsmitglied konvertiert werden soll. |

### Rückgabewert

Eine Instanz der Aufzählung, die auf value gesetzt ist.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) Methode

Konvertiert das angegebene Objekt mit einem Ganzzahlwert in ein Aufzählungsmitglied.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Der aufzurufende Aufzählungstyp. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der Wert, der in ein Aufzählungsmitglied konvertiert wird. |

### Rückgabewert

Ein Aufzählungsobjekt, dessen value value ist.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [EnumValuesBase](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)