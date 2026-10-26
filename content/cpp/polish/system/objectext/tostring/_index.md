---
title: ToString()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.
type: docs
weight: 27
url: /pl/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literał do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Nullable](../../nullable/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) obiekt do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(const T\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) wartość do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(const T\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ inteligentnego wskaźnika. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) wartość do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(T\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ inteligentnego wskaźnika lub [ExceptionWrapper](../../exceptionwrapper/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T\& | Inteligentny wskaźnik lub [ExceptionWrapper](../../exceptionwrapper/) do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(T\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ skalarowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T\& | Skalarną wartość do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(T\&&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ skalarowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T\&& | Skalarną wartość do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(T\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ struktury. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T\& | Wartość struktury do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(const T\&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ struktury. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | Wartość struktury do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## ObjectExt::ToString(T\&&) metoda

Zastąpienie metody C# ToString umożliwiające działanie na dowolnym typie C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | typ skalarowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T\&& | Skalarną wartość do konwersji na ciąg znaków. |

### Wartość zwracana

[String](../../string/) reprezentacja **obj**.

## Zobacz także

* Klasa [String](../../string/)
* Klasa [ObjectExt](../)
* Klasa [Nullable](../../nullable/)
* Struktura [IsSmartPtr](../../issmartptr/)
* Struktura [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)