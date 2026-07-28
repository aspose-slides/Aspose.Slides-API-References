---
title: GetType()
second_title: Aspose.Slides C++ API referenciája
description: Megvalósítja a typeof() fordítást. Túlterhelés okos mutatókhoz.
type: docs
weight: 1
url: /hu/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) method

Megvalósítja a typeof() fordítást. Túlterhelés okos mutatókhoz.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Mutató objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a [TypeInfo](../../typeinfo/) megszerzéséhez. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a átadott objektum végső osztályát írja le.

## ObjectType::GetType(const T\&) method

Megvalósítja a typeof() fordítást. Túlterhelés struktúrákhoz.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Struktúra típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a [TypeInfo](../../typeinfo/) megszerzéséhez. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a átadott objektum végső osztályát írja le.

## ObjectType::GetType(const T\&) method

Megvalósítja a typeof() fordítást. Túlterhelés kivételekhez.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Kivétel típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a [TypeInfo](../../typeinfo/) megszerzéséhez. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a átadott objektum végső osztályát írja le.

## ObjectType::GetType(const T) method

Megvalósítja a typeof() fordítást. Túlterhelés primitív típusokhoz.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Primitív típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T | FIGYELMEN KÍVÜL |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a átadott objektum típusát írja le.

## ObjectType::GetType(const T) method

Megvalósítja a typeof() fordítást. Túlterhelés a [Nullable](../../nullable/) típusokhoz.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Nullable](../../nullable/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T | FIGYELMEN KÍVÜL |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a átadott objektum típusát írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés primitív típusokhoz.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Primitív típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a megadott típust írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés felsorolt típusokhoz.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Primitív típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a megadott típust írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés struktúrákhoz és mutatókhoz.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Primitív típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a megadott struktúrát írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés a [Nullable](../../nullable/) típushoz.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Nullable](../../nullable/) típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a megadott struktúrát írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés MulticastDelegate-hez.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | MulticastDelegate típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a megadott struktúrát írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés struktúrákhoz és mutatókhoz.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Primitív típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a megadott struktúrát írja le, vagy a pontot típusát, ha a [SmartPtr](../../smartptr/)-t hívják.

## ObjectType::GetType(const String\&) method

Megvalósítja a typeof() fordítást. Túlterhelés string típushoz.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Primitív típus. |

### Visszatérési érték

Konstans referencia a [TypeInfo](../../typeinfo/) struktúrára, amely a [String](../../string/) típust írja le.

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés **uint8_t** típushoz.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés char16_t típushoz.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés **int32_t** típushoz.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés **int64_t** típushoz.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés bool típushoz.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() method

Megvalósítja a typeof() fordítást. Túlterhelés [Void](../../void/) típushoz.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Lásd még

* Class [ObjectType](../)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Struct [IsBoxable](../../isboxable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)