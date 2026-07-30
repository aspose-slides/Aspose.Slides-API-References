---
title: String()
second_title: Aspose.Slides pro C++ reference API
description: Výchozí konstruktor. Vytvoří objekt řetězce, který je považován za null.
type: docs
weight: 14
url: /cs/system/string/string/
---
## String::String() konstruktor

Výchozí konstruktor. Vytvoří objekt řetězce, který je považován za null.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) konstruktor

Vytvoří řetězec na základě řetězcového literálu. Považuje literál za řetězec ukončený nulou, vypočítá cílovou délku řetězce na základě velikosti literálu.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T\& | [String](../) ukazatel na literál. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) konstruktor

Vytvoří řetězec na základě ukazatele na znakový řetězec. Považuje ukazovaný řetězec za řetězec ukončený nulou, vypočítá cílovou délku řetězce na základě nulového znaku.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | Ukazatel na znakový řetězec. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) konstruktor

Vytvoří řetězec na základě řetězcového literálu. Považuje literál za řetězec ukončený nulou v UTF-8, vypočítá cílovou délku řetězce na základě velikosti literálu.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T\& | [String](../) ukazatel na literál. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) konstruktor

Vytvoří řetězec na základě ukazatele na znakový řetězec. Považuje ukazovaný řetězec za řetězec ukončený nulou v UTF-8, vypočítá cílovou délku řetězce na základě nulového znaku.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | Ukazatel na znakový řetězec. |

## String::String(const char16_t *, int) konstruktor

Vytvoří řetězec z ukazatele na znakový řetězec a explicitní délky.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const char16_t * | [String](../) ukazatel, může být literál nebo pole. |
| length | int | Explicitní délka řetězce |

## String::String(const ReadOnlySpan\<char16_t\>\&) konstruktor

Inicializuje novou instanci třídy [System.String](../) s Unicode znaky uvedenými ve specifikovaném jen pro čtení rozsahu.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Rozsah jen pro čtení Unicode znaků. |

## String::String(const char *, int) konstruktor

Vytvoří řetězec z ukazatele na znakový řetězec a explicitní délky.

```cpp
System::String::String(const char *str, int length)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const char * | [String](../) ukazatel na data UTF-8, může být literál nebo pole. |
| length | int | Explicitní délka řetězce |

## String::String(const char16_t *, int, int) konstruktor

Vytvoří řetězec z ukazatele na znakový řetězec od počáteční pozice s použitím délky.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const char16_t * | [String](../) ukazatel, může být literál nebo pole. |
| start | int | Počáteční pozice. |
| length | int | [String](../) délka. |

## String::String(const char16_t, int) konstruktor

Konstruktor výplně.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ch | const char16_t | Znak výplně. |
| count | int | Cílová délka. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) konstruktor

Konstruktor nullptr. Deklarován jako šablona pro vyřešení priorit s ostatními šablonovými konstruktory.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Měl být nullptr_t |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) konstruktor

Vytvoří řetězec na základě widestring literálu. Považuje literál za řetězec ukončený nulou, vypočítá cílovou délku řetězce na základě velikosti literálu. Konverze z **wchar_t** je časově náročná na některých platformách, takže nejsou povoleny implicitní konverze.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | T\& | [String](../) ukazatel na literál. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) konstruktor

Vytvoří řetězec na základě ukazatele na široký znakový řetězec. Považuje ukazovaný řetězec za řetězec ukončený nulou, vypočítá cílovou délku řetězce na základě nulového znaku. Konverze z **wchar_t** je časově náročná na některých platformách, takže nejsou povoleny implicitní konverze.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | const T\& | Ukazatel na znakový řetězec. |

## String::String(const wchar_t *, int) konstruktor

Vytvoří řetězec z ukazatele na široký znakový řetězec a explicitní délky. Konverze z **wchar_t** je časově náročná na některých platformách, takže nejsou povoleny implicitní konverze.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) ukazatel, může být literál nebo pole. |
| length | int | Explicitní délka řetězce |

## String::String(const wchar_t, int) konstruktor

Konstruktor výplně. Konverze z **wchar_t** je časově náročná na některých platformách, takže nejsou povoleny implicitní konverze.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ch | const **wchar_t** | Znak výplně. |
| count | int | Cílová délka. |

## String::String(const String\&) konstruktor

Konstruktor kopie.

```cpp
System::String::String(const String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) ke kopírování. |

## String::String(String\&&) konstruktor

Konstruktor přesunu.

```cpp
System::String::String(String &&str) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) k přesunu dat z. |

## String::String(const ArrayPtr\<char16_t\>\&) konstruktor

Převádí celý pole znaků na řetězec.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) k převodu na řetězec. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) konstruktor

Převádí podrozsah pole znaků na řetězec. Pokud jsou parametry mimo hranice pole, vytvoří se prázdný řetězec.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Pole znaků. |
| offset | int | Index začátku podpole. |
| len | int | Délka podpole. |

## String::String(const codeporting_icu::UnicodeString\&) konstruktor

Zabaluje UnicodeString do [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString k zabalení do [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) konstruktor

Konstruktor přesunu.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString k zabalení do [String](../). |

## String::String(const std::wstring\&) konstruktor

Vytváří [String](../) z widestringu.

```cpp
System::String::String(const std::wstring &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const std::wstring\& | Widestring k převodu na [String](../). |

## String::String(const std::u16string\&) konstruktor

Vytváří [String](../) z utf16 řetězce.

```cpp
System::String::String(const std::u16string &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const std::u16string\& | Utf16 řetězec k převodu na [String](../). |

## String::String(const std::string\&) konstruktor

Vytváří [String](../) z std::string řetězce v formátu UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| utf8str | const std::string\& | std::string řetězec k převodu na [String](../). |

## String::String(const std::u32string\&) konstruktor

Vytváří [String](../) z std::u32string řetězce.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string řetězec k převodu na [String](../). |

## Viz také

* Definice typu [ArrayPtr](../../arrayptr/)
* Třída [String](../)
* Třída [ReadOnlySpan](../../readonlyspan/)
* Struktura [IsStringLiteral](../../isstringliteral/)
* Struktura [IsStringPointer](../../isstringpointer/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)