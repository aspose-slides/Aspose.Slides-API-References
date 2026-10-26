---
title: Is()
second_title: Aspose.Slides voor C++ API Referentie
description: Implementeert de vertaling van de 'is' operator. Specialisatie voor boxbare (waarde) types die precies dat zijn.
type: docs
weight: 92
url: /nl/system/objectext/is/
---
## ObjectExt::Is(const T\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor boxbare (waarde) types die precies dat zijn.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) om te testen op de 'is' operator. Genegeerd. |

### Retourwaarde

Altijd waar

## ObjectExt::Is(const U\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor pointertypes geoptimaliseerd voor 'final' klassen.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |
| U | Getest type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const U\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor pointertypes.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |
| U | Getest type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const Object\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor waarde types.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const Object\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor niet-converteerbare types.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Retourneert altijd false omdat de types niet converteerbaar zijn.

## ObjectExt::Is(const SmartPtr\<U\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor pointertypes.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor exception-wrapper types.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor nullable types.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor boxbare types met gedefinieerde == operator.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const SmartPtr\<Object\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor boxbare types zonder gedefinieerde ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const SmartPtr\<V\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor waarde types verpakt in interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |
| V | Type van het gepointerde object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const SmartPtr\<U\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor enum types.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |
| U | Type van het gepointerde object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const WeakPtr\<U\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor enum types versus weak pointers.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |
| U | Type van het gepointerde object. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) om te testen op de 'is' operator. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const Nullable\<U\>\&) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor [Nullable](../../nullable/) type.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) type. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(const char16_t *) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor string literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## ObjectExt::Is(int32_t) methode


Implementeert de vertaling van de 'is' operator. Specialisatie voor integer literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Doeltype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int32_t** | integer literal. |

### Retourwaarde

Waar als 'is' true retourneert, anders false.

## Zie ook

* Klasse [ObjectExt](../)
* Klasse [Object](../../object/)
* Klasse [SmartPtr](../../smartptr/)
* Klasse [ExceptionWrapper](../../exceptionwrapper/)
* Klasse [WeakPtr](../../weakptr/)
* Klasse [Nullable](../../nullable/)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Bibliotheek [Aspose.Slides](../../../)