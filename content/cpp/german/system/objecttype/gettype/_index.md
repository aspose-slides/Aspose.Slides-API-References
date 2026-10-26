---
title: GetType()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementiert die typeof()-Übersetzung. Überladung für Smart-Pointer.
type: docs
weight: 1
url: /de/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) Methode

Implementiert die typeof()-Übersetzung. Überladung für Smart-Pointer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Zeigerobjekttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) zum Erhalten von [TypeInfo](../../typeinfo/) für. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die endgültige Klasse des übergebenen Objekts beschreibt.

## ObjectType::GetType(const T\&) Methode

Implementiert die typeof()-Übersetzung. Überladung für Strukturen.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Strukturtyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) zum Erhalten von [TypeInfo](../../typeinfo/) für. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die endgültige Klasse des übergebenen Objekts beschreibt.

## ObjectType::GetType(const T\&) Methode

Implementiert die typeof()-Übersetzung. Überladung für Ausnahmen.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Ausnahmetyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) zum Erhalten von [TypeInfo](../../typeinfo/) für. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die endgültige Klasse des übergebenen Objekts beschreibt.

## ObjectType::GetType(const T) Methode

Implementiert die typeof()-Übersetzung. Überladung für Primitive Typen.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Primitiver Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T | IGNORED |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die den Typ des übergebenen Objekts beschreibt.

## ObjectType::GetType(const T) Methode

Implementiert die typeof()-Übersetzung. Überladung für [Nullable](../../nullable/) Typen.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Nullable](../../nullable/) Typ. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const T | IGNORED |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die den Typ des übergebenen Objekts beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für Primitive Typen.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Primitiver Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die den angegebenen Typ beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für Aufzählungstypen.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Primitiver Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die den angegebenen Typ beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für Strukturen und Zeiger.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Primitiver Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die angegebene Struktur beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | [Nullable](../../nullable/) Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die angegebene Struktur beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | MutlicastDelegate Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die angegebene Struktur beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für Strukturen und Zeiger.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Primitiver Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die die angegebene Struktur beschreibt oder Zeigertyp, falls für [SmartPtr](../../smartptr/) aufgerufen.

## ObjectType::GetType(const String\&) Methode

Implementiert die typeof()-Übersetzung. Überladung für Zeichenkettentyp.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Primitiver Typ. |

### Rückgabewert

Konstante Referenz auf [TypeInfo](../../typeinfo/) Struktur, die den [String](../../string/) Typ beschreibt.

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() Methode

Implementiert die typeof()-Übersetzung. Überladung für [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Siehe auch

* Class [ObjectType](../)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Struct [IsBoxable](../../isboxable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)