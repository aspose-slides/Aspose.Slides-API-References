---
title: String()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Konstruktor domyślny. Tworzy obiekt string, który jest traktowany jako null.
type: docs
weight: 14
url: /pl/system/string/string/
---
## String::String() konstruktor

Konstruktor domyślny. Tworzy obiekt String, który jest traktowany jako null.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) konstruktor

Tworzy String na podstawie literału ciągu znaków. Traktuje literał jako łańcuch zakończony znakiem null, oblicza docelową długość ciągu na podstawie rozmiaru literału.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T\& | [String](../) wskaźnik literału. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) konstruktor

Tworzy String na podstawie wskaźnika na ciąg znaków. Traktuje wskazywany ciąg jako zakończony znakiem null, oblicza docelową długość ciągu na podstawie znaku null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | Wskaźnik ciągu znaków. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) konstruktor

Tworzy String na podstawie literału ciągu znaków. Traktuje literał jako łańcuch zakończony znakiem null w UTF-8, oblicza docelową długość ciągu na podstawie rozmiaru literału.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T\& | [String](../) wskaźnik literału. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) konstruktor

Tworzy String na podstawie wskaźnika na ciąg znaków. Traktuje wskazywany ciąg jako zakończony znakiem null w UTF-8, oblicza docelową długość ciągu na podstawie znaku null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | Wskaźnik ciągu znaków. |

## String::String(const char16_t *, int) konstruktor

Tworzy String z wskaźnika na ciąg znaków i podanej długości.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const char16_t * | [String](../) wskaźnik, może być literałem lub tablicą. |
| length | int | Jawna długość ciągu |

## String::String(const ReadOnlySpan\<char16_t\>\&) konstruktor

Inicjalizuje nową instancję klasy [System.String](../) znakami Unicode wskazanymi w określonym odczytowym zakresie.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Jedno-kierunkowy odczytowy zakres znaków Unicode. |

## String::String(const char *, int) konstruktor

Tworzy String z wskaźnika na ciąg znaków i podanej długości.

```cpp
System::String::String(const char *str, int length)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const char * | [String](../) wskaźnik na dane UTF-8, może być literałem lub tablicą. |
| length | int | Jawna długość ciągu |

## String::String(const char16_t *, int, int) konstruktor

Tworzy String z wskaźnika na ciąg znaków, począwszy od podanej pozycji, używając długości.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const char16_t * | [String](../) wskaźnik, może być literałem lub tablicą. |
| start | int | Pozycja początkowa. |
| length | int | [String](../) długość. |

## String::String(const char16_t, int) konstruktor

Konstruktor wypełniania.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ch | const char16_t | Znak wypełnienia. |
| count | int | Docelowa długość. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) konstruktor

Konstruktor nullptr. Zadeklarowany jako szablon w celu rozstrzygnięcia priorytetów względem innych szablonowych konstruktorów.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Powinien być nullptr_t |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) konstruktor

Tworzy String na podstawie literału szerokiego ciągu znaków. Traktuje literał jako łańcuch zakończony znakiem null, oblicza docelową długość ciągu na podstawie rozmiaru literału. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie dopuszcza się konwersji niejawnych.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T\& | [String](../) wskaźnik literału. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) konstruktor

Tworzy String na podstawie wskaźnika na szeroki ciąg znaków. Traktuje wskazywany ciąg jako zakończony znakiem null, oblicza docelową długość ciągu na podstawie znaku null. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie dopuszcza się konwersji niejawnych.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | const T\& | Wskaźnik ciągu znaków. |

## String::String(const wchar_t *, int) konstruktor

Tworzy String z wskaźnika na szeroki ciąg znaków i podanej długości. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie dopuszcza się konwersji niejawnych.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) wskaźnik, może być literałem lub tablicą. |
| length | int | Jawna długość ciągu |

## String::String(const wchar_t, int) konstruktor

Konstruktor wypełniania. Konwersja z **wchar_t** jest czasochłonna na niektórych platformach, dlatego nie dopuszcza się konwersji niejawnych.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ch | const **wchar_t** | Znak wypełnienia. |
| count | int | Docelowa długość. |

## String::String(const String\&) konstruktor

Konstruktor kopiujący.

```cpp
System::String::String(const String &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) do skopiowania. |

## String::String(String\&&) konstruktor

Konstruktor przenoszący.

```cpp
System::String::String(String &&str) noexcept
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) do przeniesienia danych z. |

## String::String(const ArrayPtr\<char16_t\>\&) konstruktor

Konwertuje całą tablicę znaków na String.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) do konwersji na String. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) konstruktor

Konwertuje podzakres tablicy znaków na String. Jeśli parametry wykraczają poza granice tablicy, tworzony jest pusty String.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Tablica znaków. |
| offset | int | Indeks początkowy podtablicy. |
| len | int | Długość podtablicy. |

## String::String(const codeporting_icu::UnicodeString\&) konstruktor

Opakowuje UnicodeString w [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString do opakowania w [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) konstruktor

Konstruktor przenoszący.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString do opakowania w [String](../). |

## String::String(const std::wstring\&) konstruktor

Tworzy [String](../) z widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const std::wstring\& | Widestring do konwersji na [String](../). |

## String::String(const std::u16string\&) konstruktor

Tworzy [String](../) z ciągu utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const std::u16string\& | Ciąg Utf16 do konwersji na [String](../). |

## String::String(const std::string\&) konstruktor

Tworzy [String](../) z ciągu std::string przedstawionego w formacie UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| utf8str | const std::string\& | ciąg std::string do konwersji na [String](../). |

## String::String(const std::u32string\&) konstruktor

Tworzy [String](../) z ciągu std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| u32str | const std::u32string\& | ciąg std::u32string do konwersji na [String](../). |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)