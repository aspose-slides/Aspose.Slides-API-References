---
title: Write()
second_title: Riferimento API Aspose.Slides per C++
description: Scrive la rappresentazione stringa dell'oggetto specificato sullo stream.
type: docs
weight: 105
url: /it/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metodo


Scrive la rappresentazione stringa dell'oggetto specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'oggetto da scrivere |

## TextWriter::Write(bool) metodo


Scrive la rappresentazione stringa del valore booleano specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **bool** | Il valore da scrivere |

## TextWriter::Write(char_t) metodo


Scrive il carattere specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Il valore da scrivere |

## TextWriter::Write(Decimal) metodo


Scrive la rappresentazione stringa dell'oggetto [Decimal](../../../system/decimal/) specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | L'oggetto da scrivere |

## TextWriter::Write(double) metodo


Scrive la rappresentazione stringa del valore a virgola mobile a doppia precisione specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da scrivere |

## TextWriter::Write(int) metodo


Scrive la rappresentazione stringa del valore intero a 32 bit specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | Il valore da scrivere |

## TextWriter::Write(int64_t) metodo


Scrive la rappresentazione stringa del valore intero a 64 bit specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int64_t** | Il valore da scrivere |

## TextWriter::Write(float) metodo


Scrive la rappresentazione stringa del valore a virgola mobile a precisione singola specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da scrivere |

## TextWriter::Write(const String\&) metodo


Scrive la stringa specificata sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La stringa da scrivere |

## TextWriter::Write(uint32_t) metodo


Scrive la rappresentazione stringa del valore intero senza segno a 32 bit specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint32_t** | Il valore da scrivere |

## TextWriter::Write(uint64_t) metodo


Scrive la rappresentazione stringa del valore intero senza segno a 64 bit specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint64_t** | Il valore da scrivere |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metodo


Scrive tutti i caratteri dall'array specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo


Scrive il sottointervallo specificato di caratteri UTF-16 dall'array di caratteri specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |
| index | **int32_t** | Un indice basato su 0 dell'elemento in **buffer** al quale inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di caratteri nel sottointervallo da scrivere; -1 specifica che il sottointervallo termina dove termina l'array **buffer** |

## TextWriter::Write(const char_t *) metodo


Scrive la c-stringa specificata sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-stringa da scrivere |

## TextWriter::Write(const TypeInfo\&) metodo


Scrive la rappresentazione stringa dell'oggetto [TypeInfo](../../../system/typeinfo/) specificato sullo stream.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | L'oggetto da scrivere |

## TextWriter::Write(const String\&, const TArgs\&...) metodo


Scrive i valori specificati formattati secondo il formato specificato sullo stream.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TArgs | L'elenco dei tipi dei valori da scrivere |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Il formato della stringa |
| args | const TArgs\&... | I valori da scrivere |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [TextWriter](../)
* Classe [Decimal](../../../system/decimal/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)