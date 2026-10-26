---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Escreve a representação em string do objeto especificado no fluxo.
type: docs
weight: 105
url: /pt/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) método


Escreve a representação em string do objeto especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | O objeto a ser escrito |

## TextWriter::Write(bool) método


Escreve a representação em string do valor booleano especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **bool** | O valor a ser escrito |

## TextWriter::Write(char_t) método


Escreve o caractere especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | O valor a ser escrito |

## TextWriter::Write(Decimal) método


Escreve a representação em string do objeto [Decimal](../../../system/decimal/) especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | O objeto a ser escrito |

## TextWriter::Write(double) método


Escreve a representação em string do valor de ponto flutuante de dupla precisão especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | O valor a ser escrito |

## TextWriter::Write(int) método


Escreve a representação em string do valor inteiro de 32 bits especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int | O valor a ser escrito |

## TextWriter::Write(int64_t) método


Escreve a representação em string do valor inteiro de 64 bits especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **int64_t** | O valor a ser escrito |

## TextWriter::Write(float) método


Escreve a representação em string do valor de ponto flutuante de precisão simples especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser escrito |

## TextWriter::Write(const String\&) método


Escreve a string especificada no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | A string a ser escrita |

## TextWriter::Write(uint32_t) método


Escreve a representação em string do valor inteiro sem sinal de 32 bits especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint32_t** | O valor a ser escrito |

## TextWriter::Write(uint64_t) método


Escreve a representação em string do valor inteiro sem sinal de 64 bits especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint64_t** | O valor a ser escrito |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) método


Escreve todos os caracteres do array especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | O array contendo os caracteres a serem escritos |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método


Escreve o sub-intervalo especificado de caracteres UTF-16 do array de caracteres especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | O array contendo os caracteres a serem escritos |
| index | **int32_t** | Um índice baseado em zero do elemento em **buffer** onde o sub-intervalo a ser escrito começa |
| count | **int32_t** | O número de caracteres no sub-intervalo a ser escrito; -1 indica que o sub-intervalo termina onde o array **buffer** termina |

## TextWriter::Write(const char_t *) método


Escreve a cadeia C-string especificada no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A C-string a ser escrita |

## TextWriter::Write(const TypeInfo\&) método


Escreve a representação em string do objeto [TypeInfo](../../../system/typeinfo/) especificado no fluxo.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | O objeto a ser escrito |

## TextWriter::Write(const String\&, const TArgs\&...) método


Escreve os valores especificados formatados de acordo com o formato especificado no fluxo.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| TArgs | A lista de tipos dos valores a serem escritos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | O formato da string |
| args | const TArgs\&... | Os valores a serem escritos |

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [TextWriter](../)
* Classe [Decimal](../../../system/decimal/)
* Classe [String](../../../system/string/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)