---
title: Concat()
second_title: Riferimento API Aspose.Slides per C++
description: Concatena un array di stringhe.
type: docs
weight: 1
url: /it/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) funzione

Concatena un array di stringhe.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) di stringhe da unire. |

### Valore di ritorno

Stringa congiunta.

## System::StringExtra::Concat(const String\&, const String\&) funzione

Concatena stringhe.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Prima stringa da concatenare. |
| str1 | const [String](../../system/string/)\& | Seconda stringa da concatenare. |

### Valore di ritorno

Stringhe parametri congiunte.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) funzione

Concatena stringhe.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Prima stringa da concatenare. |
| str1 | const [String](../../system/string/)\& | Seconda stringa da concatenare. |
| str2 | const [String](../../system/string/)\& | Terza stringa da concatenare. |

### Valore di ritorno

Stringhe parametri congiunte.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) funzione

Concatena stringhe.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Prima stringa da concatenare. |
| str1 | const [String](../../system/string/)\& | Seconda stringa da concatenare. |
| str2 | const [String](../../system/string/)\& | Terza stringa da concatenare. |
| str3 | const [String](../../system/string/)\& | Quarta stringa da concatenare. |

### Valore di ritorno

Stringhe parametri congiunte.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funzione

Converte più oggetti in stringa e concatena le stringhe risultanti. Specializzazione per tipi [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) da convertire e unire. |

### Valore di ritorno

[String](../../system/string/) valore unito dalle rappresentazioni stringa di tutti gli oggetti passati.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funzione

Converte più oggetti in stringa e concatena le stringhe risultanti. Specializzazione per tipi aritmetici.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) da convertire e unire. |

### Valore di ritorno

[String](../../system/string/) valore unito dalle rappresentazioni stringa di tutti gli oggetti passati.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) funzione

Converte più oggetti in stringa e concatena le stringhe risultanti. Specializzazione per strutture e altri tipi valore.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) da convertire e unire. |

### Valore di ritorno

[String](../../system/string/) valore unito dalle rappresentazioni stringa di tutti gli oggetti passati.

## Vedi anche

* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [String](../../system/string/)
* Struttura [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Libreria [Aspose.Slides](../../)