---
title: ObjectToUnknown()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Object in einen unbekannten Typ und behandelt sowohl Smart-Pointer-Typen als auch verpackte Wert-Situationen.
type: docs
weight: 131
url: /de/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) Methode

Konvertiert [Object](../../object/) in einen unbekannten Typ und behandelt sowohl Smart-Pointer-Typen als auch verpackte Wert-Situationen.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, in den [Object](../../object/) konvertiert werden soll. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) zum Konvertieren. |

### Rückgabewert

Entweder ein unverpackter Wert oder ein konvertierter Zeiger.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) Methode

Konvertiert [Object](../../object/) in einen unbekannten Typ und behandelt sowohl Smart-Pointer-Typen als auch verpackte Wert-Situationen.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, in den [Object](../../object/) konvertiert werden soll. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) zum Konvertieren. |

### Rückgabewert

Entweder ein unverpackter Wert oder ein konvertierter Zeiger.

## Siehe auch

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)