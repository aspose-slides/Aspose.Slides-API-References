---
title: Unbox()
second_title: Aspose.Slides voor C++ API-referentie
description: Unboxt waardetypen na conversie naar Object. Implementatie voor enum-typen.
type: docs
weight: 53
url: /nl/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxt waardetypen na conversie naar [Object](../../object/). Implementatie voor enum-typen.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te unboxen. |

### Retourwaarde

[Enum](../../enum/) waarde.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxt waardetypen na conversie naar [Object](../../object/). Implementatie voor niet-enum- en niet-nullbare typen.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Value type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te unboxen. |

### Retourwaarde

Gedeboxte waarde.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxt waardetypen na conversie naar [Object](../../object/). Implementatie voor niet-enum- en niet-nullbare typen.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Value type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te unboxen. |

### Retourwaarde

Gedeboxte waarde.

## ObjectExt::Unbox(E) method


Unboxt enum-typen naar een geheel getal.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Destination integer type. |
| E | Source enum type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| e | E | Value to unbox. |

### Retourwaarde

Integerrepresentatie van enum.

## ObjectExt::Unbox(E) method


Converteert enum-typen.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Destination enum type. |
| E | Source enum type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| e | E | Value to unbox. |

### Retourwaarde

Geconverteerde enum-waarde.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxt tekenreekswaarden.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te unboxen |

### Retourwaarde

[String](../../string/) representatie van een verpakte tekenreeks, kan null zijn als de verpakte tekenreeks null was.

## Zie ook

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Klasse [String](../../string/)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)