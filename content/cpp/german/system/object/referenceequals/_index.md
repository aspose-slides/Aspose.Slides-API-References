---
title: ReferenceEquals()
second_title: Aspose.Slides für C++ API-Referenz
description: "Spezialisierung von Object::ReferenceEquals für den Fall von string und nullptr."
type: docs
weight: 261
url: /de/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) Methode


Spezialisierung von [Object::ReferenceEquals](./) für den Fall von string und nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) zum Vergleich mit nullptr. |

### Rückgabewert

true wenn der String null ist, false sonst.

## Object::ReferenceEquals(String const\&, String const\&) Methode


Spezialisierung von [Object::ReferenceEquals](./) für den Fall von Strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Erster String zum Vergleich. |
| str2 | [String](../../string/) const\& | Zweiter String zum Vergleich. |

### Rückgabewert

true wenn die Strings übereinstimmen, false sonst.

## Object::ReferenceEquals(ptr const\&, ptr const\&) Methode


Vergleicht Objekte nach Referenz.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Erster Zeiger zum Vergleich. |
| objB | [ptr](../ptr/) const\& | Zweiter Zeiger zum Vergleich. |

### Rückgabewert

True wenn Zeiger übereinstimmen und false sonst.

## Object::ReferenceEquals(T const\&, T const\&) Methode


Vergleicht Objekte nach Referenz.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ der zu vergleichenden Objekte. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | T const\& | Erstes Objekt zum Vergleich. |
| objB | T const\& | Zweites Objekt zum Vergleich. |

### Rückgabewert

True wenn Objektadressen übereinstimmen und false sonst.

## Object::ReferenceEquals(T const\&, std::nullptr_t) Methode


Vergleicht Referenz eines Werttyp-Objekts mit nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des zu vergleichenden Objekts. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| objA | T const\& | Erstes Objekt zum Vergleich. |

### Rückgabewert

Gibt immer false zurück, da Werttypen nicht null sein können.

## Siehe auch

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)