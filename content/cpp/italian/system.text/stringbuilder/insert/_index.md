---
title: Insert()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce la stringa nella posizione fissa del builder.
type: docs
weight: 183
url: /it/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String&) metodo


Inserisce la stringa nella posizione fissa del builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Posizione in cui inserire i caratteri. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) da inserire. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Insert(int32_t, const String&, int32_t) metodo


Inserisce una stringa ripetuta nella posizione fissa del builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Posizione in cui inserire i caratteri. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) da inserire. |
| count | **int32_t** | Quante volte ripetere la stringa **value**. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Insert(int, char_t) metodo


Inserisce il carattere nella posizione fissa del builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Posizione in cui inserire i caratteri. |
| ch | char_t | Carattere da inserire. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) metodo


Inserisce caratteri nella posizione fissa del builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Posizione in cui inserire i caratteri. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) da inserire dalla fetta. |
| startIndex | int | [Array](../../../system/array/) indice iniziale della fetta. |
| charCount | int | [Array](../../../system/array/) lunghezza della fetta. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Insert(int, T) metodo


Inserisce il valore nella posizione fissa del builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Parameter | tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | Posizione in cui inserire i caratteri. |
| value | T | Valore da formattare e inserire. |

### Valore di ritorno

Questo puntatore.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Namespace [System::Text](../../)
* Libreria [Aspose.Slides](../../../)