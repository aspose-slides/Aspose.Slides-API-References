---
title: Unbox()
second_title: Aspose.Slides C++ API referencia
description: Az értéktípusok kicsomagolása az Object típusra konvertálás után. Megvalósítás enum típusokhoz.
type: docs
weight: 53
url: /hu/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metódus

A értéktípusokat kicsomagolja a [Object](../../object/) típusra konvertálás után. Megvalósítás enum típusokhoz.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | [Enum](../../enum/) típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a kicsomagoláshoz. |

### Visszatérési érték

[Enum](../../enum/) érték.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metódus

A értéktípusokat kicsomagolja a [Object](../../object/) típusra konvertálás után. Megvalósítás nem-enum és nem-nullálható típusokhoz.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a kicsomagoláshoz. |

### Visszatérési érték

Kicsomagolt érték.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metódus

A értéktípusokat kicsomagolja a [Object](../../object/) típusra konvertálás után. Megvalósítás nem-enum és nem-nullálható típusokhoz.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a kicsomagoláshoz. |

### Visszatérési érték

Kicsomagolt érték.

## ObjectExt::Unbox(E) metódus

Enum típusokat kicsomagolja egész számra.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél egész szám típus. |
| E | Forrás enum típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| e | E | Kicsomagolandó érték. |

### Visszatérési érték

Az enum egész szám reprezentációja.

## ObjectExt::Unbox(E) metódus

Enum típusokat konvertál.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Cél enum típus. |
| E | Forrás enum típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| e | E | Kicsomagolandó érték. |

### Visszatérési érték

Konvertált enum érték.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metódus

String értékeket kicsomagolja.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) a kicsomagoláshoz |

### Visszatérési érték

[String](../../string/) a dobozott string reprezentációja, null lehet, ha a dobozott string null volt.

## Lásd még

* Osztály [SmartPtr](../../smartptr/)
* Osztály [Object](../../object/)
* Osztály [ObjectExt](../)
* Osztály [String](../../string/)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)