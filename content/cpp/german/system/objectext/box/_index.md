---
title: Box()
second_title: Aspose.Slides für C++ API-Referenz
description: Boxen von Wertetypen zur Konvertierung zu Object. Implementierung für Enum-Typen.
type: docs
weight: 40
url: /de/system/objectext/box/
---
## ObjectExt::Box(const T\&) Methode


Boxt Wertetypen für die Konvertierung zu [Object](../../object/). Implementierung für Enum-Typen.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Enum](../../enum/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) Wert zum Boxen. |

### Rückgabewert

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const T\&) Methode


Boxt Wertetypen für die Konvertierung zu [Object](../../object/). Implementierung für Nicht-Enum-Typen.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Wertetyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | Wert zum Boxen. |

### Rückgabewert

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const T\&) Methode


Boxt [Nullable](../../nullable/)-Typen für die Konvertierung zu [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Wertetyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | Wert zum Boxen. |

### Rückgabewert

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const String\&) Methode


Boxt Zeichenkettenwerte.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Wert zum Boxen. |

### Rückgabewert

Gepackter Wert oder null, wenn die Quellzeichenkette null ist.

## Siehe auch

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Klasse [String](../../string/)
* Struktur [IsNullable](../../isnullable/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)