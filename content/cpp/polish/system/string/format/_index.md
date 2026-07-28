---
title: Format()
second_title: Aspose.Slides for C++ – dokumentacja API
description: Formatuje ciąg znaków w stylu C#.
type: docs
weight: 885
url: /pl/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) metoda

Formatuje ciąg znaków w stylu C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Args | Argumenty do formatowania ciągu znaków. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dostawca formatu używany do konwersji argumentów na ciągi znaków. |
| format | const [String](../)\& | Ciąg formatu. |
| args | const Args\&... | Argumenty do formatowania ciągu znaków. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) metoda

Formatuje ciąg znaków w stylu C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Args | Argumenty do formatowania ciągu znaków. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | std::nullptr_t | Ciąg formatu. |
| args | const [String](../)\& | Argumenty do formatowania ciągu znaków. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) metoda

Formatuje ciąg znaków w stylu C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Args | Argumenty do formatowania ciągu znaków. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | std::nullptr_t | Ciąg formatu. |
| args | const char16_t(&) | Argumenty do formatowania ciągu znaków. |

## String::Format(const String\&, const Args\&...) metoda

Formatuje ciąg znaków w stylu C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| Args | Argumenty do formatowania ciągu znaków. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../)\& | Ciąg formatu. |
| args | const Args\&... | Argumenty do formatowania ciągu znaków. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) metoda

Formatuje ciąg znaków w stylu C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Argumenty do formatowania ciągu znaków. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| format | const [String](../)\& | Ciąg formatu. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argumenty do formatowania ciągu znaków. |

## Zobacz także

* Definicja typu [SharedPtr](../../sharedptr/)
* Definicja typu [ArrayPtr](../../arrayptr/)
* Klasa [String](../)
* Klasa [IFormatProvider](../../iformatprovider/)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)