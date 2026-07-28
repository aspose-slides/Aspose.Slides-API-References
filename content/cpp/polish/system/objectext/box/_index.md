---
title: Box()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Opakowuje typy wartości w celu konwersji do Object. Implementacja dla typów wyliczeniowych.
type: docs
weight: 40
url: /pl/system/objectext/box/
---
## ObjectExt::Box(const T\&) metoda


Opakowuje typy wartości w celu konwersji do [Object](../../object/). Implementacja dla typów wyliczeniowych.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | [Enum](../../enum/) typ. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) wartość do opakowania. |

### Wartość zwracana

Inteligentny wskaźnik do obiektu przechowującego opakowaną wartość.

## ObjectExt::Box(const T\&) metoda


Opakowuje typy wartości w celu konwersji do [Object](../../object/). Implementacja dla typów nie-wyliczeniowych.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | Wartość do opakowania. |

### Wartość zwracana

Inteligentny wskaźnik do obiektu przechowującego opakowaną wartość.

## ObjectExt::Box(const T\&) metoda


Opakowuje typy [Nullable](../../nullable/) w celu konwersji do [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | Wartość do opakowania. |

### Wartość zwracana

Inteligentny wskaźnik do obiektu przechowującego opakowaną wartość.

## ObjectExt::Box(const String\&) metoda


Opakowuje wartości tekstowe.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [String](../../string/)\& | Wartość do opakowania. |

### Wartość zwracana

Wartość opakowana lub null, jeśli źródłowy ciąg jest null.

## Zobacz także

* Klasa [SmartPtr](../../smartptr/)
* Klasa [Object](../../object/)
* Klasa [ObjectExt](../)
* Klasa [String](../../string/)
* Struktura [IsNullable](../../isnullable/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)