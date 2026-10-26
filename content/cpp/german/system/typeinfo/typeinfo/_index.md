---
title: TypeInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Standardkonstruktor (kein Typ ist festgelegt).
type: docs
weight: 40
url: /de/system/typeinfo/typeinfo/
---
## TypeInfo::TypeInfo() Konstruktor

Standardkonstruktor (kein Typ ist festgelegt).

```cpp
System::TypeInfo::TypeInfo()
```

## TypeInfo::TypeInfo(std::nullptr_t) Konstruktor

Null-Objekt-Konstruktor (kein Typ ist festgelegt).

```cpp
System::TypeInfo::TypeInfo(std::nullptr_t)
```

## TypeInfo::TypeInfo(const char_t *) Konstruktor

Konstruktor.

```cpp
System::TypeInfo::TypeInfo(const char_t *name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const char_t * | Typname. |

## TypeInfo::TypeInfo(const char_t *, uint32_t) Konstruktor

Konstruktor.

```cpp
System::TypeInfo::TypeInfo(const char_t *name, uint32_t hash)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | const char_t * | Typname. |
| hash | **uint32_t** | Hash des Typnamens. |

## TypeInfo::TypeInfo(const std::type_info\&) Konstruktor

Konstruktor.

```cpp
System::TypeInfo::TypeInfo(const std::type_info &info)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| info | const std::type_info\& | Informationen zu einem Typ. |

## Siehe auch

* Klasse [TypeInfo](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)