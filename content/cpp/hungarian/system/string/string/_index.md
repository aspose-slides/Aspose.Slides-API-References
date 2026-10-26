---
title: String()
second_title: Aspose.Slides C++ API referencia
description: Alapértelmezett konstruktor. Létrehoz egy string objektumot, amely null-nak tekinthető.
type: docs
weight: 14
url: /hu/system/string/string/
---
## String::String() konstruktor

Alapértelmezett konstruktor. Létrehoz egy string objektumot, amely null-nek tekinthető.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) konstruktor

Stringet hoz létre a karakterlánc literal alapján. A litert null-terminált karakterláncként kezeli, a célnak megfelelő karakterlánc hosszát a literal mérete alapján számítja ki.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T\& | [String](../) literal mutató. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) konstruktor

Stringet hoz létre karakterlánc mutató alapján. A mutatott karakterláncot null-termináltként kezeli, a célnak megfelelő karakterlánc hosszát a null karakter alapján számítja ki.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | Karakterlánc mutató. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) konstruktor

Stringet hoz létre a karakterlánc literal alapján. A litert UTF-8-ban null-terminált karakterláncként tekinti, a célnak megfelelő karakterlánc hosszát a literal mérete alapján számítja ki.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T\& | [String](../) literal mutató. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) konstruktor

Stringet hoz létre karakterlánc mutató alapján. A mutatott karakterláncot UTF-8-ban null-termináltként kezeli, a célnak megfelelő karakterlánc hosszát a null karakter alapján számítja ki.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | Karakterlánc mutató. |

## String::String(const char16_t *, int) konstruktor

Stringet hoz létre karakterlánc mutatóból és kifejezett hosszból.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const char16_t * | [String](../) mutató, lehet literal vagy tömb. |
| length | int | Kifejezett karakterlánc hossza |

## String::String(const ReadOnlySpan\<char16_t\>\&) konstruktor

Inicializál egy új példányt a [System.String](../) osztályból a megadott csak-olvasható tartományban jelzett Unicode karakterekkel.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Unicode karakterek csak-olvasható tartománya. |

## String::String(const char *, int) konstruktor

Stringet hoz létre karakterlánc mutatóból és kifejezett hosszból.

```cpp
System::String::String(const char *str, int length)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const char * | [String](../) mutató az UTF-8 adatra, lehet literal vagy tömb. |
| length | int | Kifejezett karakterlánc hossza |

## String::String(const char16_t *, int, int) konstruktor

Stringet hoz létre karakterlánc mutatóból, a kezdőpozíciótól a megadott hossz szerint.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const char16_t * | [String](../) mutató, lehet literal vagy tömb. |
| start | int | Kezdő pozíció. |
| length | int | [String](../) hossz. |

## String::String(const char16_t, int) konstruktor

Kitöltő konstruktor.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | const char16_t | Kitöltő karakter. |
| count | int | Célhossz. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) konstruktor

Nullptr konstruktor. Sablonként van deklarálva a többi sablonkonstruktorral való prioritásfeloldás érdekében.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | nullptr_t kell legyen |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) konstruktor

Stringet hoz létre széles karakterlánc literal alapján. A litert null-terminált karakterláncként kezeli, a célnak megfelelő karakterlánc hosszát a literal mérete alapján számítja ki. A **wchar_t** konverzió egyes platformokon időigényes, ezért nem engedélyezett az implicit konverzió.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | T\& | [String](../) literal mutató. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) konstruktor

Stringet hoz létre széles karakterlánc mutató alapján. A mutatott karakterláncot null-termináltként kezeli, a célnak megfelelő karakterlánc hosszát a null karakter alapján számítja ki. A **wchar_t** konverzió egyes platformokon időigényes, ezért nem engedélyezett az implicit konverzió.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const T\& | Karakterlánc mutató. |

## String::String(const wchar_t *, int) konstruktor

Stringet hoz létre széles karakterlánc mutatóból és kifejezett hosszból. A **wchar_t** konverzió egyes platformokon időigényes, ezért nem engedélyezett az implicit konverzió.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) mutató, lehet literal vagy tömb. |
| length | int | Kifejezett karakterlánc hossza |

## String::String(const wchar_t, int) konstruktor

Kitöltő konstruktor. A **wchar_t** konverzió egyes platformokon időigényes, ezért nem engedélyezett az implicit konverzió.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ch | const **wchar_t** | Kitöltő karakter. |
| count | int | Célhossz. |

## String::String(const String\&) konstruktor

Másoló konstruktor.

```cpp
System::String::String(const String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) másoláshoz. |

## String::String(String\&&) konstruktor

Áthelyező konstruktor.

```cpp
System::String::String(String &&str) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) az adat áthelyezéséhez. |

## String::String(const ArrayPtr\<char16_t\>\&) konstruktor

Átalakítja a teljes karaktertömböt stringgé.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) a stringgé alakításhoz. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) konstruktor

Átalakítja a karaktertömb részhalmazát stringgé. Ha a paraméterek a tömbhatáron kívül esnek, üres stringet hoz létre.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Karaktertömb. |
| offset | int | Alttömb kezdőindexe. |
| len | int | Alttömb hossza. |

## String::String(const codeporting_icu::UnicodeString\&) konstruktor

UnicodeString-et becsomagolja a [String](../)-ba.

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString, amit a [String](../)-ba csomagol. |

## String::String(codeporting_icu::UnicodeString\&&) konstruktor

Áthelyező konstruktor.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString, amit a [String](../)-ba csomagol. |

## String::String(const std::wstring\&) konstruktor

[String](../) létrehozása widestringből.

```cpp
System::String::String(const std::wstring &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const std::wstring\& | Widestring, amit a [String](../)-ba konvertál. |

## String::String(const std::u16string\&) konstruktor

[String](../) létrehozása utf16 stringből.

```cpp
System::String::String(const std::u16string &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const std::u16string\& | Utf16 string, amit a [String](../)-ba konvertál. |

## String::String(const std::string\&) konstruktor

[String](../) létrehozása UTF-8 formátumú std::stringből.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| utf8str | const std::string\& | std::string string, amit a [String](../)-ba konvertál. |

## String::String(const std::u32string\&) konstruktor

[String](../) létrehozása std::u32stringből.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string string, amit a [String](../)-ba konvertál. |

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)