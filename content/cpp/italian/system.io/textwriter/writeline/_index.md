---
title: WriteLine()
second_title: Aspose.Slides per C++ Riferimento API
description: Scrive i caratteri di terminazione di riga nel flusso.
type: docs
weight: 118
url: /it/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() metodo


Scrive i caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) metodo


Scrive la rappresentazione stringa dell'oggetto specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'oggetto da scrivere |

## TextWriter::WriteLine(bool) metodo


Scrive la rappresentazione stringa del valore booleano specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **bool** | Il valore da scrivere |

## TextWriter::WriteLine(char_t) metodo


Scrive il carattere specificato seguito dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Il valore da scrivere |

## TextWriter::WriteLine(Decimal) metodo


Scrive la rappresentazione stringa dell'oggetto [Decimal](../../../system/decimal/) specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | L'oggetto da scrivere |

## TextWriter::WriteLine(double) metodo


Scrive la rappresentazione stringa del valore a virgola mobile a doppia precisione specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **double** | Il valore da scrivere |

## TextWriter::WriteLine(int) metodo


Scrive la rappresentazione stringa del valore intero a 32 bit specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int | Il valore da scrivere |

## TextWriter::WriteLine(int64_t) metodo


Scrive la rappresentazione stringa del valore intero a 64 bit specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **int64_t** | Il valore da scrivere |

## TextWriter::WriteLine(float) metodo


Scrive la rappresentazione stringa del valore a virgola mobile a precisione singola specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **float** | Il valore da scrivere |

## TextWriter::WriteLine(const String\&) metodo


Scrive la stringa specificata seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La stringa da scrivere |

## TextWriter::WriteLine(uint32_t) metodo


Scrive la rappresentazione stringa del valore intero senza segno a 32 bit specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint32_t** | Il valore da scrivere |

## TextWriter::WriteLine(uint64_t) metodo


Scrive la rappresentazione stringa del valore intero senza segno a 64 bit specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | **uint64_t** | Il valore da scrivere |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) metodo


Scrive tutti i caratteri dall'array specificato seguiti dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo


Scrive il sottointervallo specificato di caratteri UTF-16 dall'array di caratteri specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |
| index | **int32_t** | Un indice base-0 dell'elemento in **buffer** da cui inizia il sottointervallo da scrivere |
| count | **int32_t** | Il numero di caratteri nel sottointervallo da scrivere; -1 indica che il sottointervallo termina dove termina l'array **buffer** |

## TextWriter::WriteLine(const char_t *) metodo


Scrive la c-string specificata seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const char_t * | La c-string da scrivere |

## TextWriter::WriteLine(const TypeInfo\&) metodo


Scrive la rappresentazione stringa dell'oggetto [TypeInfo](../../../system/typeinfo/) specificato seguita dai caratteri di terminazione di riga nello stream.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | L'oggetto da scrivere |

## TextWriter::WriteLine(const String\&, const TArgs\&...) metodo


Scrive i valori specificati formattati secondo il formato specificato seguiti dai caratteri di terminazione di riga nello stream.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| TArgs | L'elenco dei tipi di valori da scrivere |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Il formato della stringa |
| args | const TArgs\&... | I valori da scrivere |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TextWriter](../)
* Classe [Object](../../../system/object/)
* Classe [Decimal](../../../system/decimal/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)