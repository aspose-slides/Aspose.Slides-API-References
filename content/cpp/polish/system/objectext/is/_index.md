---
title: Is()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Implementuje tłumaczenie operatora 'is'. Specjalizacja dla typów pudełkowych (wartościowych), które dokładnie taki są.
type: docs
weight: 92
url: /pl/system/objectext/is/
---
## ObjectExt::Is(const T\&) metoda

Implements 'is' operator translation. Specialization for boxable (value) types which exactly is that they are.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) do testowania operatora 'is'. Ignorowane. |

### Wartość zwracana

Zawsze true

## ObjectExt::Is(const U\&) metoda

Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |
| U | Typ testowany. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const U\&) metoda

Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |
| U | Typ testowany. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const Object\&) metoda

Implements 'is' operator translation. Specialization for value types.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const Object\&) metoda

Implements 'is' operator translation. Specialization for unconvertible types.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

Zawsze zwraca false, ponieważ typy są nieprzekształcalne.

## ObjectExt::Is(const SmartPtr\<U\>\&) metoda

Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) metoda

Implements 'is' operator translation. Specialization for exception wrapper types.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metoda

Implements 'is' operator translation. Specialization for nullable types.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metoda

Implements 'is' operator translation. Specialization for boxable types with == operator defined.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metoda

Implements 'is' operator translation. Specialization for boxable types without defined ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const SmartPtr\<V\>\&) metoda

Implements 'is' operator translation. Specialization value types boxed to interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |
| V | Typ obiektu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const SmartPtr\<U\>\&) metoda

Implements 'is' operator translation. Specialization for enum types.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |
| U | Typ obiektu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const WeakPtr\<U\>\&) metoda

Implements 'is' operator translation. Specialization for enum types vs weak pointers.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |
| U | Typ obiektu wskazywanego. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) do testowania operatora 'is'. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const Nullable\<U\>\&) metoda

Implements 'is' operator translation. Specialization for [Nullable](../../nullable/) type.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) typ. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(const char16_t *) metoda

Implements 'is' operator translation. Specialization for string literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literał. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## ObjectExt::Is(int32_t) metoda

Implements 'is' operator translation. Specialization for integer literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ docelowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | **int32_t** | literał całkowity. |

### Wartość zwracana

True jeśli operator 'is' zwraca true, false w przeciwnym razie.

## Zobacz także

* Klasa [ObjectExt](../)
* Klasa [Object](../../object/)
* Klasa [SmartPtr](../../smartptr/)
* Klasa [ExceptionWrapper](../../exceptionwrapper/)
* Klasa [WeakPtr](../../weakptr/)
* Klasa [Nullable](../../nullable/)
* Struktura [IsBoxable](../../isboxable/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)