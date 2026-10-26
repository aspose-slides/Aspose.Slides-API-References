---
title: ToString()
second_title: Aspose.Slides voor C++ API-referentie
description: Vervanging voor de C# ToString-methode om te werken met elk C++-type.
type: docs
weight: 27
url: /nl/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) object om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(const T\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) waarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(const T\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Smart-pointertype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) waarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(T\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Smart-pointertype of [ExceptionWrapper](../../exceptionwrapper/). |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T\& | Smart pointer of [ExceptionWrapper](../../exceptionwrapper/) om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(T\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Scalair type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T\& | Scalair waarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(T\&&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Scalair type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T\&& | Scalair waarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(T\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Structuurtype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T\& | Structuurwaarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(const T\&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Structuurtype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | Structuurwaarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## ObjectExt::ToString(T\&&) methode


Vervanging voor de C# ToString-methode om te werken met elk C++-type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Scalair type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T\&& | Scalair waarde om te converteren naar string. |

### Retourwaarde

[String](../../string/) representatie van **obj**.

## Zie ook

* Klasse [String](../../string/)
* Klasse [ObjectExt](../)
* Klasse [Nullable](../../nullable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)