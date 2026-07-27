---
title: Write()
second_title: Referência da API Aspose.Slides para C++
description: Emite a representação em string do objeto especificado para o fluxo de saída padrão.
type: docs
weight: 1
url: /pt/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) método

Emite a representação em string do objeto especificado para o fluxo de saída padrão.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto a ser emitido |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) para ser emitido |

## Console::Write(bool) método

Emite a representação em string do valor bool para o fluxo de saída padrão.

```cpp
static void System::Console::Write(bool value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **bool** | O valor a ser emitido |

## Console::Write(char_t) método

Emite a representação em string do valor do caractere especificado para o fluxo de saída padrão.

```cpp
static void System::Console::Write(char_t value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char_t | O valor a ser emitido |

## Console::Write(const ArrayPtr\<char_t\>\&) método

Emite a representação em string do array de caracteres especificado para o fluxo de saída padrão.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | O array a ser emitido |

## Console::Write(const Decimal\&) método

Emite a representação em string do valor [Decimal](../../decimal/) para o fluxo de saída padrão.

```cpp
static void System::Console::Write(const Decimal &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | O valor a ser emitido |

## Console::Write(double) método

Emite a representação em string do valor de ponto flutuante de dupla precisão para o fluxo de saída padrão.

```cpp
static void System::Console::Write(double value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **double** | O valor a ser emitido |

## Console::Write(float) método

Emite a representação em string do valor de ponto flutuante de precisão simples para o fluxo de saída padrão.

```cpp
static void System::Console::Write(float value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **float** | O valor a ser emitido |

## Console::Write(int32_t) método

Emite a representação em string do valor inteiro de 32 bits para o fluxo de saída padrão.

```cpp
static void System::Console::Write(int32_t value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **int32_t** | O valor a ser emitido |

## Console::Write(int64_t) método

Emite a representação em string do valor inteiro de 64 bits para o fluxo de saída padrão.

```cpp
static void System::Console::Write(int64_t value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **int64_t** | O valor a ser emitido |

## Console::Write(const String\&) método

Emite o objeto string especificado para o fluxo de saída padrão.

```cpp
static void System::Console::Write(const String &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [String](../../string/)\& | O objeto string a ser emitido |

## Console::Write(const char_t *) método

Emite a c-string especificada para o fluxo de saída padrão.

```cpp
static void System::Console::Write(const char_t *value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const char_t * | A c-string a ser emitida |

## Console::Write(const TypeInfo\&) método

Emite a representação em string do valor [TypeInfo](../../typeinfo/) para o fluxo de saída padrão.

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | O valor a ser emitido |

## Console::Write(uint32_t) método

Emite a representação em string do valor inteiro sem sinal de 32 bits para o fluxo de saída padrão.

```cpp
static void System::Console::Write(uint32_t value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint32_t** | O valor a ser emitido |

## Console::Write(uint64_t) método

Emite a representação em string do valor inteiro sem sinal de 64 bits para o fluxo de saída padrão.

```cpp
static void System::Console::Write(uint64_t value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | **uint64_t** | O valor a ser emitido |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) método

Emite a representação em string do intervalo especificado da matriz de caracteres especificada para o fluxo de saída padrão.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | A matriz de caracteres |
| index | **int32_t** | O índice na matriz onde o intervalo a ser emitido começa |
| count | **int32_t** | O número de elementos no intervalo a ser emitido |

## Console::Write(const String\&, Args\&&...) método

Emite a representação em string dos argumentos especificados formatados de acordo com o formato especificado para o fluxo de saída padrão.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| Os | tipos dos valores a serem emitidos |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| format | const [String](../../string/)\& | O formato da string |
| args | Args\&&... | Os valores a serem emitidos |

## Console::Write(const char *) método




```cpp
static void System::Console::Write(const char *)=delete
```

## Veja Também

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)