---
title: Concat()
second_title: Referência da API Aspose.Slides para C++
description: Concatena um array de strings.
type: docs
weight: 1
url: /pt/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) função


Concatena um array de strings.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) de strings a serem concatenadas. |

### Valor de Retorno

String concatenada.

## System::StringExtra::Concat(const String\&, const String\&) função


Concatena strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Primeira string a ser concatenada. |
| str1 | const [String](../../system/string/)\& | Segunda string a ser concatenada. |

### Valor de Retorno

Strings dos parâmetros concatenadas.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) função


Concatena strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Primeira string a ser concatenada. |
| str1 | const [String](../../system/string/)\& | Segunda string a ser concatenada. |
| str2 | const [String](../../system/string/)\& | Terceira string a ser concatenada. |

### Valor de Retorno

Strings dos parâmetros concatenadas.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) função


Concatena strings.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Primeira string a ser concatenada. |
| str1 | const [String](../../system/string/)\& | Segunda string a ser concatenada. |
| str2 | const [String](../../system/string/)\& | Terceira string a ser concatenada. |
| str3 | const [String](../../system/string/)\& | Quarta string a ser concatenada. |

### Valor de Retorno

Strings dos parâmetros concatenadas.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) função


Converte vários objetos em string e concatena as strings resultantes. Especialização para tipos [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) para converter e concatenar. |

### Valor de Retorno

Valor [String](../../system/string/) concatenado a partir das representações em string de todos os objetos passados.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) função


Converte vários objetos em string e concatena as strings resultantes. Especialização para tipos aritméticos.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) para converter e concatenar. |

### Valor de Retorno

Valor [String](../../system/string/) concatenado a partir das representações em string de todos os objetos passados.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) função


Converte vários objetos em string e concatena as strings resultantes. Especialização para estruturas e outros tipos de valor.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) para converter e concatenar. |

### Valor de Retorno

Valor [String](../../system/string/) concatenado a partir das representações em string de todos os objetos passados.

## Veja Também

* Typedef [ArrayPtr](../../system/arrayptr/)
* Classe [String](../../system/string/)
* Estrutura [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Biblioteca [Aspose.Slides](../../)