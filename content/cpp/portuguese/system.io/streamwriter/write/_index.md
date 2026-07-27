---
title: Write()
second_title: Aspose.Slides para C++ Referência da API
description: Escreve o caractere especificado no fluxo.
type: docs
weight: 79
url: /pt/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) método


Escreve o caractere especificado no fluxo.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | O caractere a ser escrito |

## StreamWriter::Write(const String\&) método


Escreve a string especificada no fluxo.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | A string a ser escrita |

## StreamWriter::Write(const SharedPtr\<Object\>\&) método


Escreve a representação em string do objeto especificado no fluxo.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | O objeto a ser escrito |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) método


Escreve todos os caracteres do array especificado no fluxo.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | O array contendo os caracteres a serem escritos |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método


Escreve o subintervalo especificado de caracteres UTF-16 do array de caracteres especificado no fluxo.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | O array contendo os caracteres a serem escritos |
| index | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o subintervalo a ser escrito começa |
| count | **int32_t** | O número de caracteres no subintervalo a ser escrito; -1 especifica que o subintervalo termina onde o array **buffer** termina |

## StreamWriter::Write(const char_t *) método


Escreve a c-string especificada no fluxo.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const char_t * | A c-string a ser escrita |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) método


Escreve a representação em string do objeto especificado no fluxo.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo do objeto |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | O objeto a ser escrito |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StreamWriter](../)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)