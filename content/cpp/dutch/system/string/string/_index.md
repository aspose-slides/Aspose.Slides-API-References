---
title: String()
second_title: Aspose.Slides voor C++ API-referentie
description: Standaardconstructor. Maakt een stringobject dat als null wordt beschouwd.
type: docs
weight: 14
url: /nl/system/string/string/
---
## String::String() constructor

Standaardconstructor. Maakt een stringobject dat als null wordt beschouwd.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) constructor

Construeert een string op basis van een stringliteral. Beschouwt de literal als een null-terminerende string, berekent de doelstringlengte op basis van de grootte van de literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T\& | [String](../) letterlijke pointer. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) constructor

Construeert een string op basis van een karakterstringpointer. Beschouwt de aangewezen string als null-terminerend, berekent de doelstringlengte op basis van het null-teken.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | Karakterstringpointer. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) constructor

Construeert een string op basis van een stringliteral. Beschouwt de literal als een null-terminerende string in UTF-8, berekent de doelstringlengte op basis van de grootte van de literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T\& | [String](../) letterlijke pointer. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) constructor

Construeert een string op basis van een karakterstringpointer. Beschouwt de aangewezen string als null-terminerend in UTF-8, berekent de doelstringlengte op basis van het null-teken.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | Karakterstringpointer. |

## String::String(const char16_t *, int) constructor

Construeert een string vanuit een karakterstringpointer en een expliciete lengte.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, kan een literal of een array zijn. |
| length | int | Expliciete stringlengte |

## String::String(const ReadOnlySpan\<char16_t\>\&) constructor

Initialiseert een nieuw exemplaar van de [System.String](../) klasse met de Unicode-tekens aangeduid in de gespecificeerde read-only-span.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Een read-only-span van Unicode-tekens. |

## String::String(const char *, int) constructor

Construeert een string vanuit een karakterstringpointer en een expliciete lengte.

```cpp
System::String::String(const char *str, int length)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const char * | [String](../) pointer naar de UTF-8-data, kan een literal of een array zijn. |
| length | int | Expliciete stringlengte |

## String::String(const char16_t *, int, int) constructor

Construeert een string vanuit een karakterstringpointer vanaf een startpositie met een opgegeven lengte.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, kan een literal of een array zijn. |
| start | int | Startpositie. |
| length | int | [String](../) lengte. |

## String::String(const char16_t, int) constructor

Vulconstructor.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ch | const char16_t | Vul-karakter. |
| count | int | Doellengte. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) constructor

Nullptr-constructor. Gedeclareerd als template om prioriteiten met andere template-constructors op te lossen.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Moet nullptr_t zijn |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) constructor

Construeert een string op basis van een widestring-literal. Beschouwt de literal als een null-terminerende string, berekent de doelstringlengte op basis van de grootte van de literal. Conversie van **wchar_t** kost veel tijd op sommige platforms, dus impliciete conversies zijn niet toegestaan.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T\& | [String](../) letterlijke pointer. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) constructor

Construeert een string op basis van een widecharacter-stringpointer. Beschouwt de aangewezen string als null-terminerend, berekent de doelstringlengte op basis van het null-teken. Conversie van **wchar_t** kost veel tijd op sommige platforms, dus impliciete conversies zijn niet toegestaan.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const T\& | Karakterstringpointer. |

## String::String(const wchar_t *, int) constructor

Construeert een string vanuit een widecharacter-stringpointer en een expliciete lengte. Conversie van **wchar_t** kost veel tijd op sommige platforms, dus impliciete conversies zijn niet toegestaan.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) pointer, kan een literal of een array zijn. |
| length | int | Expliciete stringlengte |

## String::String(const wchar_t, int) constructor

Vulconstructor. Conversie van **wchar_t** kost veel tijd op sommige platforms, dus impliciete conversies zijn niet toegestaan.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ch | const **wchar_t** | Vul-karakter. |
| count | int | Doellengte. |

## String::String(const String\&) constructor

Copy-constructor.

```cpp
System::String::String(const String &str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) om te kopiëren. |

## String::String(String\&&) constructor

Move-constructor.

```cpp
System::String::String(String &&str) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) om gegevens vanuit te verplaatsen. |

## String::String(const ArrayPtr\<char16_t\>\&) constructor

Converteert een volledige karakterarray naar een string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) om te converteren naar een string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) constructor

Converteert een subreeks van een karakterarray naar een string. Als parameters buiten de array-grenzen vallen, wordt een lege string geconstrueerd.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Karakterarray. |
| offset | int | Beginindex van de subarray. |
| len | int | Lengte van de subarray. |

## String::String(const codeporting_icu::UnicodeString\&) constructor

Wrapt UnicodeString in [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString om in [String](../) te wrappen. |

## String::String(codeporting_icu::UnicodeString\&&) constructor

Move-constructor.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString om in [String](../) te wrappen. |

## String::String(const std::wstring\&) constructor

Creëert [String](../) vanuit een widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const std::wstring\& | Widestring om te converteren naar [String](../). |

## String::String(const std::u16string\&) constructor

Creëert [String](../) vanuit een utf16-string.

```cpp
System::String::String(const std::u16string &str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const std::u16string\& | Utf16-string om te converteren naar [String](../). |

## String::String(const std::string\&) constructor

Creëert [String](../) vanuit een std::string-string gepresenteerd in UTF-8-formaat.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| utf8str | const std::string\& | std::string-string om te converteren naar [String](../). |

## String::String(const std::u32string\&) constructor

Creëert [String](../) vanuit een std::u32string-string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string-string om te converteren naar [String](../). |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)