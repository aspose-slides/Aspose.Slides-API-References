---
title: Is()
second_title: Aspose.Slides för C++ API-referens
description: Implementerar 'is'-operatorns översättning. Specialisering för boxbara (värde) typer som exakt är det de är.
type: docs
weight: 92
url: /sv/system/objectext/is/
---
## ObjectExt::Is(const T\&) method

Implementerar 'is'-operatorns översättning. Specialisering för boxbara (värde) typer som exakt är det de är.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) för att testa 'is'-operatorn. Ignoreras. |

### Returvärde

Alltid sant

## ObjectExt::Is(const U\&) method

Implementerar 'is'-operatorns översättning. Specialisering för pekartyper optimerade för 'final'-klasser.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |
| U | Testad typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const U\&) method

Implementerar 'is'-operatorns översättning. Specialisering för pekartyper.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |
| U | Testad typ. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const Object\&) method

Implementerar 'is'-operatorns översättning. Specialisering för värdetyper.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const Object\&) method

Implementerar 'is'-operatorns översättning. Specialisering för icke-konverterbara typer.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Returnerar alltid falskt eftersom typerna är icke-konverterbara.

## ObjectExt::Is(const SmartPtr\<U\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för pekartyper.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för undantags-wrapper-typer.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för nullable-typer.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för boxbara typer med ==-operator definierad.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för boxbara typer utan definierad ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const SmartPtr\<V\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för värdetyper som boxas till interface.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |
| V | Typ av det pekade objektet. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const SmartPtr\<U\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för enum-typer.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |
| U | Typ av det pekade objektet. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const WeakPtr\<U\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för enum-typer jämfört med svaga pekare.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |
| U | Typ av det pekade objektet. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) för att testa 'is'-operatorn. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const Nullable\<U\>\&) method

Implementerar 'is'-operatorns översättning. Specialisering för [Nullable](../../nullable/)-typ.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/)-typ. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(const char16_t *) method

Implementerar 'is'-operatorns översättning. Specialisering för sträng-literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## ObjectExt::Is(int32_t) method

Implementerar 'is'-operatorns översättning. Specialisering för heltals-literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Målslag. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int32_t** | heltals-literal. |

### Returvärde

Sant om 'is' returnerar sant, annars falskt.

## Se även

* Klass [ObjectExt](../)
* Klass [Object](../../object/)
* Klass [SmartPtr](../../smartptr/)
* Klass [ExceptionWrapper](../../exceptionwrapper/)
* Klass [WeakPtr](../../weakptr/)
* Klass [Nullable](../../nullable/)
* Struktur [IsBoxable](../../isboxable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)