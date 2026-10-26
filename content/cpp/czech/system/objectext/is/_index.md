---
title: Is()
second_title: Aspose.Slides pro C++ API Reference
description: Implementuje překlad operátoru 'is'. Specializace pro boxovatelné (hodnotové) typy, které jsou přesně takové, jaké jsou.
type: docs
weight: 92
url: /cs/system/objectext/is/
---
## ObjectExt::Is(const T&) metoda


Implementuje překlad operátoru 'is'. Specializace pro boxovatelné (hodnotové) typy, které jsou přesně takové, jaké jsou.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) k testování operátoru 'is'. Ignorováno. |

### Návratová hodnota

Vždy true

## ObjectExt::Is(const U&) metoda


Implementuje překlad operátoru 'is'. Specializace pro ukazatelové typy optimalizované pro třídy označené jako 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |
| U | Testovaný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const U&) metoda


Implementuje překlad operátoru 'is'. Specializace pro ukazatelové typy.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |
| U | Testovaný typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const Object&) metoda


Implementuje překlad operátoru 'is'. Specializace pro hodnotové typy.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const Object&) metoda


Implementuje překlad operátoru 'is'. Specializace pro nekonvertovatelné typy.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

Vždy vrací false, protože typy jsou nekonvertovatelné.

## ObjectExt::Is(const SmartPtr\<U\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro ukazatelové typy.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro typy obalující výjimky.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro nullable typy.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro boxovatelné typy s definovaným operátorem ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro boxovatelné typy bez definovaného ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const SmartPtr\<V\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro hodnotové typy zabalené jako rozhraní.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |
| V | Typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const SmartPtr\<U\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro výčtové typy.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |
| U | Typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const WeakPtr\<U\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro výčtové typy vs slabé ukazatele.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |
| U | Typ ukazovaného objektu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) k testování operátoru 'is'. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const Nullable\<U\>\&) metoda


Implementuje překlad operátoru 'is'. Specializace pro typ [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) typu. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(const char16_t *) metoda


Implementuje překlad operátoru 'is'. Specializace pro řetězcový literál.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literál. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## ObjectExt::Is(int32_t) metoda


Implementuje překlad operátoru 'is'. Specializace pro celočíselný literál.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Cílový typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | **int32_t** | celočíselný literál. |

### Návratová hodnota

True pokud operátor 'is' vrátí true, jinak false.

## Viz také

* Třída [ObjectExt](../)
* Třída [Object](../../object/)
* Třída [SmartPtr](../../smartptr/)
* Třída [ExceptionWrapper](../../exceptionwrapper/)
* Třída [WeakPtr](../../weakptr/)
* Třída [Nullable](../../nullable/)
* Struktura [IsBoxable](../../isboxable/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsNullable](../../isnullable/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)