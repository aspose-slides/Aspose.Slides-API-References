---
title: GetType()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementeert typeof() vertaling. Overload voor slimme pointers.
type: docs
weight: 1
url: /nl/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) methode

Implementeert typeof() vertaling. Overload voor slimme pointers.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Pointer-objecttype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) om [TypeInfo](../../typeinfo/) te krijgen voor. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de uiteindelijke klasse van het meegegeven object beschrijft.

## ObjectType::GetType(const T\&) methode


Implementeert typeof() vertaling. Overload voor structuren.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Structuurtype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) om [TypeInfo](../../typeinfo/) te krijgen voor. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de uiteindelijke klasse van het meegegeven object beschrijft.

## ObjectType::GetType(const T\&) methode


Implementeert typeof() vertaling. Overload voor uitzonderingen.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Exceptietype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) om [TypeInfo](../../typeinfo/) te krijgen voor. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de uiteindelijke klasse van het meegegeven object beschrijft.

## ObjectType::GetType(const T) methode


Implementeert typeof() vertaling. Overload voor primitieve types.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Primitief type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T | IGNORED |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die het type van het meegegeven object beschrijft.

## ObjectType::GetType(const T) methode


Implementeert typeof() vertaling. Overload voor [Nullable](../../nullable/)-types.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T | IGNORED |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die het type van het meegegeven object beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor primitieve types.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Primitief type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die het opgegeven type beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor enum-types.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Primitief type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die het opgegeven type beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor structuren en pointers.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Primitief type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de opgegeven structuur beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de opgegeven structuur beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | MutlicastDelegate type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de opgegeven structuur beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor structuren en pointers.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Primitief type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die de opgegeven structuur beschrijft of pointee-type als dat wordt opgevraagd [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) methode


Implementeert typeof() vertaling. Overload voor string-type.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Primitief type. |

### Retourwaarde

Const-referentie naar [TypeInfo](../../typeinfo/) structuur die het [String](../../string/) type beschrijft.

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() methode


Implementeert typeof() vertaling. Overload voor [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Zie ook

* Klasse [ObjectType](../)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [String](../../string/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Struct [IsBoxable](../../isboxable/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)