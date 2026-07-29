---
title: String()
second_title: Aspose.Slides för C++ API-referens
description: Standardkonstruktör. Skapar string-objekt som anses vara null.
type: docs
weight: 14
url: /sv/system/string/string/
---
## String::String() konstruktör

Standardkonstruktör. Skapar string-objekt som anses vara null.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) konstruktör

Skapar string baserat på en strängliteral. Betraktar literalen som en null-terminerad sträng och beräknar målsträngens längd baserat på literalens storlek.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | [String](../) literalpekare. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) konstruktör

Skapar string baserat på en teckensträngpekare. Behandlar den pekade strängen som null-terminerad och beräknar målsträngens längd baserat på null-tecknet.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | Teckensträngpekare. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) konstruktör

Skapar string baserat på en strängliteral. Betraktar literalen som en null-terminerad sträng i UTF-8 och beräknar målsträngens längd baserat på literalens storlek.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | [String](../) literalpekare. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) konstruktör

Skapar string baserat på en teckensträngpekare. Behandlar den pekade strängen som null-terminerad i UTF-8 och beräknar målsträngens längd baserat på null-tecknet.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | Teckensträngpekare. |

## String::String(const char16_t *, int) konstruktör

Skapar string från teckensträngpekare och explicit längd.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char16_t * | [String](../) pekare, kan vara literal eller array. |
| length | int | Explicit stränglängd |

## String::String(const ReadOnlySpan\<char16_t\>\&) konstruktör

Initierar en ny instans av [System.String](../)-klassen till Unicode-tecknen som anges i den specificerade skrivskyddade spanen.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | En skrivskyddad span av Unicode-tecken. |

## String::String(const char *, int) konstruktör

Skapar string från teckensträngpekare och explicit längd.

```cpp
System::String::String(const char *str, int length)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char * | [String](../) pekare till UTF-8-data, kan vara literal eller array. |
| length | int | Explicit stränglängd |

## String::String(const char16_t *, int, int) konstruktör

Skapar string från teckensträngpekare med startposition och angiven längd.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const char16_t * | [String](../) pekare, kan vara literal eller array. |
| start | int | Startposition. |
| length | int | [String](../) längd. |

## String::String(const char16_t, int) konstruktör

Fyll-konstruktör.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | const char16_t | Fylltecken. |
| count | int | Mållängd. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) konstruktör

Nullptr-konstruktör. Deklarerad som mall för att lösa prioriteringar med andra mall-konstruktörer.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Ska vara nullptr_t |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) konstruktör

Skapar string baserat på en widestring-literal. Betraktar literalen som en null-terminerad sträng och beräknar målsträngens längd baserat på literalens storlek. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | T\& | [String](../) literalpekare. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) konstruktör

Skapar string baserat på en wide-teckensträngpekare. Behandlar den pekade strängen som null-terminerad och beräknar målsträngens längd baserat på null-tecknet. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const T\& | Wide-teckensträngpekare. |

## String::String(const wchar_t *, int) konstruktör

Skapar string från wide-teckensträngpekare och explicit längd. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) pekare, kan vara literal eller array. |
| length | int | Explicit stränglängd |

## String::String(const wchar_t, int) konstruktör

Fyll-konstruktör. Konvertering från **wchar_t** är tidskrävande på vissa plattformar, så inga implicita konverteringar tillåts.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ch | const **wchar_t** | Fylltecken. |
| count | int | Mållängd. |

## String::String(const String\&) konstruktör

Kopieringskonstruktör.

```cpp
System::String::String(const String &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) att kopiera. |

## String::String(String\&&) konstruktör

Flyttkonstruktör.

```cpp
System::String::String(String &&str) noexcept
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) att flytta data från. |

## String::String(const ArrayPtr\<char16_t\>\&) konstruktör

Konverterar hela teckenarrayen till string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) att konvertera till string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) konstruktör

Konverterar ett delintervall av teckenarrayen till string. Om parametrarna är utanför arrayens gränser skapas en tom string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Teckenarray. |
| offset | int | Startindex för delarray. |
| len | int | Längd för delarray. |

## String::String(const codeporting_icu::UnicodeString\&) konstruktör

Packar in UnicodeString i [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString att packa in i [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) konstruktör

Flyttkonstruktör.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString att packa in i [String](../). |

## String::String(const std::wstring\&) konstruktör

Skapar [String](../) från widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const std::wstring\& | Widestring att konvertera till [String](../). |

## String::String(const std::u16string\&) konstruktör

Skapar [String](../) från utf16-sträng.

```cpp
System::String::String(const std::u16string &str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const std::u16string\& | Utf16-sträng att konvertera till [String](../). |

## String::String(const std::string\&) konstruktör

Skapar [String](../) från std::string-sträng i formatet UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| utf8str | const std::string\& | std::string-sträng att konvertera till [String](../). |

## String::String(const std::u32string\&) konstruktör

Skapar [String](../) från std::u32string-sträng.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string-sträng att konvertera till [String](../). |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Klass [String](../)
* Klass [ReadOnlySpan](../../readonlyspan/)
* Struktur [IsStringLiteral](../../isstringliteral/)
* Struktur [IsStringPointer](../../isstringpointer/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)