---
title: Append()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge un carattere al builder.
type: docs
weight: 118
url: /it/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metodo


Aggiunge un carattere al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | char_t | Valore del carattere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(char_t, int) metodo


Aggiunge caratteri al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| c | char_t | Valore del carattere. |
| count | int | Quante volte ripetere il carattere inserito. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) metodo


Aggiunge un array di caratteri al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caratteri da aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metodo


Aggiunge una porzione di array di caratteri al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Caratteri da aggiungere. |
| startIndex | int | Indice iniziale della porzione. |
| charCount | int | Lunghezza della porzione. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(const String\&) metodo


Aggiunge una stringa al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) da aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(const String\&, int, int) metodo


Aggiunge una porzione di stringa al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) da aggiungere. |
| startIndex | int | Indice iniziale della porzione. |
| charCount | int | Lunghezza della porzione. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(const SharedPtr\<T\>\&) metodo


Aggiunge la rappresentazione stringa dell'oggetto al builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | [Object](../../../system/object/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) da serializzare e aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metodo


Aggiunge il contenuto del builder al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder da cui aggiungere il contenuto. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(float) metodo


Aggiunge un valore in virgola mobile al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| f | **float** | Valore da serializzare e aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(double) metodo


Aggiunge un valore in virgola mobile al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| df | **double** | Valore da serializzare e aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(int) metodo


Aggiunge un valore intero al builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| i | int | Valore da serializzare e aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(T) metodo


Aggiunge un valore aritmetico al builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo aritmetico. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | T | Valore da serializzare e aggiungere. |

### Valore di ritorno

Questo puntatore.

## StringBuilder::Append(E) metodo


Aggiunge la rappresentazione stringa del valore enum al builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| E | [Enum](../../../system/enum/) tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| e | E | Valore da serializzare e aggiungere. |

### Valore di ritorno

Questo puntatore.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [StringBuilder](../)
* Classe [String](../../../system/string/)
* Namespace [System::Text](../../)
* Libreria [Aspose.Slides](../../../)