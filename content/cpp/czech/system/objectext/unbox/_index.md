---
title: Unbox()
second_title: Aspose.Slides pro C++ API Reference
description: Rozbaluje typy hodnot po převodu na Object. Implementace pro výčtové typy.
type: docs
weight: 53
url: /cs/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda

Rozbalí typy hodnot po převodu na [Object](../../object/). Implementace pro výčtové typy.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k rozbalení. |

### Návratová hodnota

[Enum](../../enum/) hodnota.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda

Rozbalí typy hodnot po převodu na [Object](../../object/). Implementace pro typy, které nejsou výčtové a nejsou nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k rozbalení. |

### Návratová hodnota

Rozbalená hodnota.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda

Rozbalí typy hodnot po převodu na [Object](../../object/). Implementace pro typy, které nejsou výčtové a nejsou nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ hodnoty. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k rozbalení. |

### Návratová hodnota

Rozbalená hodnota.

## ObjectExt::Unbox(E) metoda

Rozbalí výčtové typy na celé číslo.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ celého čísla. |
| E | Zdrojový výčtový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| e | E | Hodnota k rozbalení. |

### Návratová hodnota

Celé číselné vyjádření výčtu.

## ObjectExt::Unbox(E) metoda

Převádí výčtové typy.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový výčtový typ. |
| E | Zdrojový výčtový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| e | E | Hodnota k rozbalení. |

### Návratová hodnota

Převedená hodnota výčtu.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metoda

Rozbalí řetězcové hodnoty.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k rozbalení |

### Návratová hodnota

[String](../../string/) reprezentace zabaleného řetězce, může být null, pokud byl zabalený řetězec null.

## Viz také

* Třída [SmartPtr](../../smartptr/)
* Třída [Object](../../object/)
* Třída [ObjectExt](../)
* Třída [String](../../string/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)