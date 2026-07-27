---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Escreve o valor inteiro sem sinal de 8-bit especificado no fluxo de saída.
type: docs
weight: 92
url: /pt/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) método


Escreve o valor inteiro sem sinal de 8 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint8_t** | O valor a ser escrito |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) método


Escreve o sub-intervalo especificado de bytes do array de bytes especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array contendo os bytes a serem escritos |
| index | int | Um índice baseado em 0 do elemento em **buffer** onde o sub-intervalo a ser escrito começa |
| count | int | O número de elementos no sub-intervalo a ser escrito; -1 indica que o sub-intervalo termina onde o array **buffer** termina |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) método


Escreve o sub-intervalo especificado de caracteres UTF-16 do array de caracteres especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | O array contendo os caracteres a serem escritos |
| index | int | Um índice baseado em 0 do elemento em **buffer** onde o sub-intervalo a ser escrito começa |
| count | int | O número de caracteres no sub-intervalo a ser escrito; -1 indica que o sub-intervalo termina onde o array **buffer** termina |

## BinaryWriter::Write(bool) método


Escreve um único byte com valor 0 se **value** for 'true' e 1 se **value** for 'false no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **bool** | O valor booleano que especifica o byte a ser escrito no fluxo de saída |

## BinaryWriter::Write(char16_t) método


Escreve o caractere de 16 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char16_t | O valor a ser escrito |

## BinaryWriter::Write(int16_t) método


Escreve o valor inteiro de 16 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **int16_t** | O valor a ser escrito |

## BinaryWriter::Write(int) método


Escreve o valor inteiro de 32 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int | O valor a ser escrito |

## BinaryWriter::Write(int64_t) método


Escreve o valor inteiro de 64 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **int64_t** | O valor a ser escrito |

## BinaryWriter::Write(uint16_t) método


Escreve o valor inteiro sem sinal de 16 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint16_t** | O valor a ser escrito |

## BinaryWriter::Write(uint32_t) método


Escreve o valor inteiro sem sinal de 32 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint32_t** | O valor a ser escrito |

## BinaryWriter::Write(uint64_t) método


Escreve o valor inteiro sem sinal de 64 bits especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint64_t** | O valor a ser escrito |

## BinaryWriter::Write(float) método


Escreve o valor de ponto flutuante de precisão simples especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser escrito |

## BinaryWriter::Write(double) método


Escreve o valor de ponto flutuante de precisão dupla especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | O valor a ser escrito |

## BinaryWriter::Write(const Decimal\&) método


Escreve a representação em bytes do valor [Decimal](../../../system/decimal/) especificado no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | O valor a ser escrito |

## BinaryWriter::Write(const String\&) método


Escreve uma string prefixada por comprimento na codificação atual no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | A string a ser escrita |

## BinaryWriter::Write(const char_t *) método


Escreve uma string prefixada por comprimento na codificação atual no fluxo de saída.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A cadeia C a ser escrita |

## Ver Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [BinaryWriter](../)
* Classe [Decimal](../../../system/decimal/)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)