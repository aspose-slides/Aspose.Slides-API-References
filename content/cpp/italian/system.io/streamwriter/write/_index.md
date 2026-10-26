---
title: Write()
second_title: Riferimento API di Aspose.Slides per C++
description: Scrive il carattere specificato nello stream.
type: docs
weight: 79
url: /it/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metodo


Scrive il carattere specificato nello stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char_t | Il carattere da scrivere |


## StreamWriter::Write(const String\&) metodo


Scrive la stringa specificata nello stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | La stringa da scrivere |


## StreamWriter::Write(const SharedPtr\<Object\>\&) metodo


Scrive la rappresentazione testuale dell'oggetto specificato nello stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'oggetto da scrivere |


## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metodo


Scrive tutti i caratteri dall'array specificato nello stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |


## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metodo


Scrive l'intervallo specificato di caratteri UTF-16 dall'array di caratteri specificato nello stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | L'array contenente i caratteri da scrivere |
| index | **int32_t** | Un indice a base 0 dell'elemnet in **buffer** al quale inizia l'intervallo da scrivere |
| count | **int32_t** | Il numero di caratteri nell'intervallo da scrivere; -1 indica che l'intervallo termina dove termina l'array **buffer** |


## StreamWriter::Write(const char_t *) metodo


Scrive la c-string specificata nello stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const char_t * | La c-string da scrivere |


## StreamWriter::Write(const System::SharedPtr\<T\>\&) metodo


Scrive la rappresentazione testuale dell'oggetto specificato nello stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Il tipo dell'oggetto |


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | L'oggetto da scrivere |


## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)