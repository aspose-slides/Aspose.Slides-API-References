---
title: String()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruttore predefinito. Crea un oggetto stringa considerato nullo.
type: docs
weight: 14
url: /it/system/string/string/
---
## String::String() costruttore

Costruttore predefinito. Crea l'oggetto stringa considerato nullo.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) costruttore

Costruisce una stringa basata su un literal di stringa. Considera il literal una stringa terminata da null, calcola la lunghezza della stringa destinazione in base alle dimensioni del literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T\& | [String](../) puntatore al literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) costruttore

Costruisce una stringa basata su un puntatore a stringa di caratteri. Tratta la stringa puntata come terminata da null, calcola la lunghezza della stringa destinazione in base al carattere null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | Puntatore a stringa di caratteri. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) costruttore

Costruisce una stringa basata su un literal di stringa. Considera il literal una stringa terminata da null in UTF-8, calcola la lunghezza della stringa destinazione in base alle dimensioni del literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T\& | [String](../) puntatore al literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) costruttore

Costruisce una stringa basata su un puntatore a stringa di caratteri. Tratta la stringa puntata come terminata da null in UTF-8, calcola la lunghezza della stringa destinazione in base al carattere null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | Puntatore a stringa di caratteri. |

## String::String(const char16_t *, int) costruttore

Costruisce una stringa da un puntatore a stringa di caratteri e una lunghezza esplicita.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const char16_t * | [String](../) puntatore, può essere un literal o un array. |
| length | int | Lunghezza esplicita della stringa |

## String::String(const ReadOnlySpan\<char16_t\>\&) costruttore

Inizializza una nuova istanza della classe [System.String](../) con i caratteri Unicode indicati nello span di sola lettura specificato.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Uno span di sola lettura di caratteri Unicode. |

## String::String(const char *, int) costruttore

Costruisce una stringa da un puntatore a stringa di caratteri e una lunghezza esplicita.

```cpp
System::String::String(const char *str, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const char * | [String](../) puntatore ai dati UTF-8, può essere un literal o un array. |
| length | int | Lunghezza esplicita della stringa |

## String::String(const char16_t *, int, int) costruttore

Costruisce una stringa da un puntatore a stringa di caratteri a partire da una posizione iniziale usando la lunghezza.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const char16_t * | [String](../) puntatore, può essere un literal o un array. |
| start | int | Posizione iniziale. |
| length | int | [String](../) lunghezza. |

## String::String(const char16_t, int) costruttore

Costruttore di riempimento.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ch | const char16_t | Carattere di riempimento. |
| count | int | Lunghezza target. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) costruttore

Costruttore nullptr. Dichiarato come modello per risolvere le priorità con altri costruttori modello.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Dovrebbe essere nullptr_t |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) costruttore

Costruisce una stringa basata su un literal widestring. Considera il literal una stringa terminata da null, calcola la lunghezza della stringa destinazione in base alle dimensioni del literal. La conversione da **wchar_t** è dispendiosa in tempo su alcune piattaforme, quindi non sono consentite conversioni implicite.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T\& | [String](../) puntatore al literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) costruttore

Costruisce una stringa basata su un puntatore a stringa widecharacter. Tratta la stringa puntata come terminata da null, calcola la lunghezza della stringa destinazione in base al carattere null. La conversione da **wchar_t** è dispendiosa in tempo su alcune piattaforme, quindi non sono consentite conversioni implicite.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const T\& | Puntatore a stringa di caratteri. |

## String::String(const wchar_t *, int) costruttore

Costruisce una stringa da un puntatore a stringa widecharacter e una lunghezza esplicita. La conversione da **wchar_t** è dispendiosa in tempo su alcune piattaforme, quindi non sono consentite conversioni implicite.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) puntatore, può essere un literal o un array. |
| length | int | Lunghezza esplicita della stringa |

## String::String(const wchar_t, int) costruttore

Costruttore di riempimento. La conversione da **wchar_t** è dispendiosa in tempo su alcune piattaforme, quindi non sono consentite conversioni implicite.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ch | const **wchar_t** | Carattere di riempimento. |
| count | int | Lunghezza target. |

## String::String(const String\&) costruttore

Costruttore di copia.

```cpp
System::String::String(const String &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) da copiare. |

## String::String(String\&&) costruttore

Costruttore di spostamento.

```cpp
System::String::String(String &&str) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) da cui spostare i dati. |

## String::String(const ArrayPtr\<char16_t\>\&) costruttore

Converte l'intero array di caratteri in una stringa.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) da convertire in stringa. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) costruttore

Converte un sottointervallo di un array di caratteri in una stringa. Se i parametri sono fuori dai limiti dell'array, viene costruita una stringa vuota.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Array di caratteri. |
| offset | int | Indice di inizio del sottoarray. |
| len | int | Lunghezza del sottoarray. |

## String::String(const codeporting_icu::UnicodeString\&) costruttore

Avvolge UnicodeString in [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString da avvolgere in [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) costruttore

Costruttore di spostamento.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString da avvolgere in [String](../). |

## String::String(const std::wstring\&) costruttore

Crea [String](../) da widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const std::wstring\& | Widestring da convertire in [String](../). |

## String::String(const std::u16string\&) costruttore

Crea [String](../) da stringa utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const std::u16string\& | Stringa Utf16 da convertire in [String](../). |

## String::String(const std::string\&) costruttore

Crea [String](../) da una stringa std::string presentata nel formato UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| utf8str | const std::string\& | Stringa std::string da convertire in [String](../). |

## String::String(const std::u32string\&) costruttore

Crea [String](../) da una stringa std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| u32str | const std::u32string\& | Stringa std::u32string da convertire in [String](../). |

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)