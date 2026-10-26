---
title: UnknownToObject()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Konwertuje nieznany typ na Object, obsługując zarówno typy wskaźników inteligentnych, jak i typy wartości.
type: docs
weight: 118
url: /pl/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) metoda

Konwertuje nieznany typ na [Object](../../object/), obsługując zarówno sytuacje typu wskaźnika inteligentnego, jak i typu wartości.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, który ma zostać przekonwertowany na [Object](../../object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | T | [Object](../../object/) do konwersji. |

### Wartość zwracana

Inteligentny wskaźnik do [Object](../../object/), będący albo przekonwertowanym wskaźnikiem, albo opakowaną wartością.

## ObjectExt::UnknownToObject(const T\&) metoda

Konwertuje nieznany typ na [Object](../../object/), obsługując zarówno sytuacje typu wskaźnika inteligentnego, jak i typu wartości.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, który ma zostać przekonwertowany na [Object](../../object/). |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) do konwersji. |

### Wartość zwracana

Inteligentny wskaźnik do [Object](../../object/), będący albo przekonwertowanym wskaźnikiem, albo opakowaną wartością.

## Zobacz także

* Klasa [SmartPtr](../../smartptr/)
* Klasa [Object](../../object/)
* Klasa [ObjectExt](../)
* Struktura [IsSmartPtr](../../issmartptr/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)