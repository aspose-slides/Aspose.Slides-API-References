---
title: UnknownToObject()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert unbekannten Typ zu Object, wobei sowohl Smart-Pointer-Typ als auch Werttyp-Situationen behandelt werden.
type: docs
weight: 118
url: /de/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) Methode


Konvertiert unbekannten Typ zu [Object](../../object/), wobei sowohl Smart-Pointer-Typen als auch Werttyp-Situationen behandelt werden.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, der in [Object](../../object/) konvertiert werden soll. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T | [Object](../../object/) zum Konvertieren. |

### Rückgabewert

Smart-Pointer zu [Object](../../object/), der entweder ein konvertierter Zeiger oder ein verpackter Wert ist.

## ObjectExt::UnknownToObject(const T\&) Methode


Konvertiert unbekannten Typ zu [Object](../../object/), wobei sowohl Smart-Pointer-Typen als auch Werttyp-Situationen behandelt werden.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, der in [Object](../../object/) konvertiert werden soll. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) zum Konvertieren. |

### Rückgabewert

Smart-Pointer zu [Object](../../object/), der entweder ein konvertierter Zeiger oder ein verpackter Wert ist.

## Siehe auch

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)