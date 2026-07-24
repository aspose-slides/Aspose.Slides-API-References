---
title: String()
second_title: Aspose.Slides für C++ API-Referenz
description: Standardkonstruktor. Erstellt ein String-Objekt, das als null betrachtet wird.
type: docs
weight: 14
url: /de/system/string/string/
---
## String::String() Konstruktor

Standardkonstruktor. Erstellt ein String-Objekt, das als null betrachtet wird.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) Konstruktor

Erzeugt einen String basierend auf einem String-Literal. Betrachtet das Literal als nullterminierten String und berechnet die Zielzeichenlänge anhand der Literalgröße.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | [String](../) Literal-Zeiger. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) Konstruktor

Erzeugt einen String basierend auf einem Zeichen-String-Zeiger. Behandelt den referenzierten String als nullterminiert und berechnet die Zielzeichenlänge anhand des Null-Zeichens.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | Zeichen-String-Zeiger. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) Konstruktor

Erzeugt einen String basierend auf einem String-Literal. Betrachtet das Literal als nullterminierten String in UTF-8 und berechnet die Zielzeichenlänge anhand der Literalgröße.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | [String](../) Literal-Zeiger. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) Konstruktor

Erzeugt einen String basierend auf einem Zeichen-String-Zeiger. Behandelt den referenzierten String als nullterminiert in UTF-8 und berechnet die Zielzeichenlänge anhand des Null-Zeichens.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | Zeichen-String-Zeiger. |

## String::String(const char16_t *, int) Konstruktor

Erzeugt einen String aus einem Zeichen-String-Zeiger und einer expliziten Länge.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char16_t * | [String](../) Zeiger, kann ein Literal oder ein Array sein. |
| length | int | Explizite String-Länge |

## String::String(const ReadOnlySpan\<char16_t\>\&) Konstruktor

Initialisiert eine neue Instanz der [System.String](../) Klasse mit den Unicode-Zeichen, die im angegebenen schreibgeschützten Span angegeben sind.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Ein schreibgeschützter Span von Unicode-Zeichen. |

## String::String(const char *, int) Konstruktor

Erzeugt einen String aus einem Zeichen-String-Zeiger und einer expliziten Länge.

```cpp
System::String::String(const char *str, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char * | [String](../) Zeiger auf die UTF-8-Daten, kann ein Literal oder ein Array sein. |
| length | int | Explizite String-Länge |

## String::String(const char16_t *, int, int) Konstruktor

Erzeugt einen String aus einem Zeichen-String-Zeiger, beginnend an der Startposition, unter Verwendung der angegebenen Länge.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const char16_t * | [String](../) Zeiger, kann ein Literal oder ein Array sein. |
| start | int | Startposition. |
| length | int | [String](../) Länge. |

## String::String(const char16_t, int) Konstruktor

Füllkonstruktor.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | const char16_t | Füllzeichen. |
| count | int | Ziellänge. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) Konstruktor

Nullptr-Konstruktor. Als Template deklariert, um Prioritäten mit anderen Template-Konstruktoren aufzulösen.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Sollte nullptr_t sein |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) Konstruktor

Erzeugt einen String basierend auf einem Wide-String-Literal. Betrachtet das Literal als nullterminierten String und berechnet die Zielzeichenlänge anhand der Literalgröße. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitintensiv, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | T\& | [String](../) Literal-Zeiger. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) Konstruktor

Erzeugt einen String basierend auf einem Wide-Char-String-Zeiger. Behandelt den referenzierten String als nullterminiert und berechnet die Zielzeichenlänge anhand des Null-Zeichens. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitintensiv, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const T\& | Zeichen-String-Zeiger. |

## String::String(const wchar_t *, int) Konstruktor

Erzeugt einen String aus einem Wide-Char-String-Zeiger und einer expliziten Länge. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitintensiv, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) Zeiger, kann ein Literal oder ein Array sein. |
| length | int | Explizite String-Länge |

## String::String(const wchar_t, int) Konstruktor

Füllkonstruktor. Die Konvertierung von **wchar_t** ist auf manchen Plattformen zeitintensiv, daher sind implizite Konvertierungen nicht erlaubt.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ch | const **wchar_t** | Füllzeichen. |
| count | int | Ziellänge. |

## String::String(const String\&) Konstruktor

Kopierkonstruktor.

```cpp
System::String::String(const String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) zum Kopieren. |

## String::String(String\&&) Konstruktor

Move-Konstruktor.

```cpp
System::String::String(String &&str) noexcept
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) zum Verschieben von Daten aus. |

## String::String(const ArrayPtr\<char16_t\>\&) Konstruktor

Konvertiert das gesamte Zeichenarray in einen String.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) zur Konvertierung in einen String. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) Konstruktor

Konvertiert einen Teilbereich eines Zeichenarrays in einen String. Wenn Parameter außerhalb des Array-Bereichs liegen, wird ein leerer String erzeugt.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Zeichenarray. |
| offset | int | Startindex des Teilarrays. |
| len | int | Länge des Teilarrays. |

## String::String(const codeporting_icu::UnicodeString\&) Konstruktor

Wickelt UnicodeString in [String](../) ein.

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString zum Einwickeln in [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) Konstruktor

Move-Konstruktor.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString zum Einwickeln in [String](../). |

## String::String(const std::wstring\&) Konstruktor

Erstellt [String](../) aus einem Wide-String.

```cpp
System::String::String(const std::wstring &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const std::wstring\& | Wide-String zur Konvertierung in [String](../). |

## String::String(const std::u16string\&) Konstruktor

Erstellt [String](../) aus einem UTF-16-String.

```cpp
System::String::String(const std::u16string &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const std::u16string\& | UTF-16-String zur Konvertierung in [String](../). |

## String::String(const std::string\&) Konstruktor

Erstellt [String](../) aus einem std::string, das im Format UTF-8 vorliegt.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| utf8str | const std::string\& | std::string zur Konvertierung in [String](../). |

## String::String(const std::u32string\&) Konstruktor

Erstellt [String](../) aus einem std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string zur Konvertierung in [String](../). |

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../)
* Klasse [ReadOnlySpan](../../readonlyspan/)
* Struktur [IsStringLiteral](../../isstringliteral/)
* Struktur [IsStringPointer](../../isstringpointer/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)