---
title: UnknownIsNull()
second_title: Aspose.Slides für C++ API Referenz
description: Überprüft, ob das Objekt unbekannten Typs nullptr ist. Überladung für nicht-skalare Typen.
type: docs
weight: 144
url: /de/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) Methode

Überprüft, ob das Objekt unbekannten Typs nullptr ist. Überladung für nicht-skalare Typen.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T | [Object](../../object/) zu prüfen. |

### Rückgabewert

Wahr, wenn 'obj == nullptr' wahr ist, sonst falsch.

## ObjectExt::UnknownIsNull(T) Methode

Überprüft, ob das Objekt unbekannten Typs nullptr ist. Überladung für skalare Typen.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Object](../../object/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | T | [Object](../../object/) zu prüfen. |

### Rückgabewert

Gibt immer false zurück.

## Siehe auch

* Klasse [ObjectExt](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)