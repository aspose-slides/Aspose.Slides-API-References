---
title: Is()
second_title: Aspose.Slides C++ API referencia
description: Megvalósítja az 'is' operátor fordítását. Specializáció a csomagolható (érték) típusokra, amelyek pontosan ennek megfelelőek.
type: docs
weight: 92
url: /hu/system/objectext/is/
---
## ObjectExt::Is(const T&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció a csomagolható (érték) típusokra, amelyek pontosan ennek megfelelőek.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a 'is' operátor teszteléséhez. Figyelmen kívül hagyva. |

### Visszatérési érték

Mindig igaz

## ObjectExt::Is(const U&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció mutató típusokra, a 'final' osztályokra optimalizálva.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |
| U | Tesztelt típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const U&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció mutató típusokra.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |
| U | Tesztelt típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const Object&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció értéktípusokra.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const Object&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció nem konvertálható típusokra.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Mindig hamis, mivel a típusok nem konvertálhatók.

## ObjectExt::Is(const SmartPtr\<U\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció mutató típusokra.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció kivételcsomagoló típusokra.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció nullable (nullázható) típusokra.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció csomagolható típusokra, ahol definiált a == operátor.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció csomagolható típusokra, ahol nincs definiált == operátor.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const SmartPtr\<V\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció értéktípusok csomagolására interfészekbe.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |
| V | A mutatott objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const SmartPtr\<U\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció enum típusokra.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |
| U | A mutatott objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const WeakPtr\<U\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció enum típusokra weak pointerekkel szemben.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |
| U | A mutatott objektum típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) a 'is' operátor teszteléséhez. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const Nullable\<U\>\&) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció a(z) [Nullable](../../nullable/) típusra.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) típus. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(const char16_t *) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció karakterlánc literálra.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literál. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## ObjectExt::Is(int32_t) metódus


Megvalósítja az 'is' operátor fordítását. Specializáció egész szám literálra.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | **int32_t** | egész szám literál. |

### Visszatérési érték

Igaz, ha az 'is' true értéket ad vissza, egyébként hamis.

## Lásd még

* Class [ObjectExt](../)
* Class [Object](../../object/)
* Class [SmartPtr](../../smartptr/)
* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [WeakPtr](../../weakptr/)
* Class [Nullable](../../nullable/)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)