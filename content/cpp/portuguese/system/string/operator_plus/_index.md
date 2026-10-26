---
title: operator+()
second_title: Referência da API Aspose.Slides para C++
description: Operador de concatenação de strings.
type: docs
weight: 274
url: /pt/system/string/operator_plus/
---
## String::operator+(const String\&) const método

[String](../) operador de concatenação.

```cpp
String System::String::operator+(const String &str) const
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) para adicionar ao final do atual. |

### Valor de retorno

String concatenada.

## String::operator+(const T\&) const método

[String](../) concatenação com literal de string ou ponteiro de string de caracteres.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Uma das formas de literal de string ou ponteiro de string de caracteres. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arg | const T\& | Entidade para concatenar com a string atual. |

### Valor de retorno

String concatenada.

## String::operator+(char_t) const método

```cpp
String System::String::operator+(char_t x) const
```
Adiciona caractere ao final da string.

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | char_t | Caractere a ser adicionado. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(int) const método

```cpp
String System::String::operator+(int i) const
```
Adiciona a representação em string de valor inteiro ao final da string.

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | int | Valor inteiro a ser convertido em string e adicionado. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(uint32_t) const método

```cpp
String System::String::operator+(uint32_t i) const
```
Adiciona a representação em string de valor inteiro sem sinal ao final da string.

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| i | **uint32_t** | Valor a ser convertido em string e adicionado. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(double) const método

```cpp
String System::String::operator+(double d) const
```
Adiciona a representação em string de valor de ponto flutuante ao final da string.

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| d | **double** | Valor a ser convertido em string e adicionado. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(int64_t) const método

```cpp
String System::String::operator+(int64_t v) const
```
Adiciona a representação em string de valor inteiro ao final da string.

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| v | **int64_t** | Valor a ser convertido em string e adicionado. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(const T\&) const método

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```
Adiciona a representação em string de objeto do tipo referência ao final da string.

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | tipo ponteiro. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) para converter em string usando chamada [ToString()](../tostring/) e adicionar à string atual. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(const T\&) const método

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```
Adiciona a representação em string de objeto do tipo valor ao final da string.

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor para chamar [ToString()](../tostring/). |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) para converter em string usando chamada [ToString()](../tostring/) e adicionar à string atual. |

### Valor de retorno

[String](../) resultado da concatenação.

## String::operator+(T) const método

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```
Adiciona a representação em string de valor booleano ao final da string.

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor para concatenar com a string. Deve ser bool |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) valor para converter em string e adicionar. |

### Valor de retorno

[String](../) resultado da concatenação.

## Veja Também

* Classe [String](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)