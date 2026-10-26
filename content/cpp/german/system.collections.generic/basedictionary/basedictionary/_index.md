---
title: BaseDictionary()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine leere Datenstruktur.
type: docs
weight: 14
url: /de/system.collections.generic/basedictionary/basedictionary/
---
## BaseDictionary::BaseDictionary() Konstruktor

Erstellt eine leere Datenstruktur.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary()
```

## BaseDictionary::BaseDictionary(int, const Args\&...) Konstruktor

Weiterleitender Konstruktor, um Argumente an den zugrunde liegenden Map-Konstruktor zu übergeben.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(int, const Args &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Typen der an die Map weiterzuleitenden Argumente. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | int | Argumente, die an den zugrunde liegenden Map-Konstruktor weitergeleitet werden. |

## BaseDictionary::BaseDictionary(BaseType *, const Args\&...) Konstruktor

Kopierkonstruktor.

```cpp
template<class...> System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src, const Args &... args)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Args | Typen der Map-Konstruktorargumente. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) zum Kopieren von. |
| args | const Args\&... | Argumente, die an den zugrunde liegenden Map-Konstruktor weitergeleitet werden. |

## BaseDictionary::BaseDictionary(BaseType *) Konstruktor

Kopierkonstruktor.

```cpp
System::Collections::Generic::BaseDictionary<Map>::BaseDictionary(BaseType *src)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src | [BaseType](../basetype/) * | [Object](../../../system/object/) zum Kopieren von. |

## Siehe auch

* Typedef [BaseType](../basetype/)
* Klasse [BaseDictionary](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)