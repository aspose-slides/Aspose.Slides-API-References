---
title: ReferenceEquals()
second_title: Referência da API Aspose.Slides para C++
description: "Especialização de Object::ReferenceEquals para o caso de string e nullptr."
type: docs
weight: 261
url: /pt/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) método


Especialização de [Object::ReferenceEquals](./) para o caso de string e nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) para comparar com nullptr. |

### Valor de Retorno

true se a string for nula, false caso contrário.

## Object::ReferenceEquals(String const\&, String const\&) método


Especialização de [Object::ReferenceEquals](./) para o caso de strings.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | Primeira string a comparar. |
| str2 | [String](../../string/) const\& | Segunda string a comparar. |

### Valor de Retorno

true se as strings coincidirem, false caso contrário.

## Object::ReferenceEquals(ptr const\&, ptr const\&) método


Compara objetos por referência.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Primeiro ponteiro a comparar. |
| objB | [ptr](../ptr/) const\& | Segundo ponteiro a comparar. |

### Valor de Retorno

True se os ponteiros coincidirem e false caso contrário.

## Object::ReferenceEquals(T const\&, T const\&) método


Compara objetos por referência.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo dos objetos a comparar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | T const\& | Primeiro objeto a comparar. |
| objB | T const\& | Segundo objeto a comparar. |

### Valor de Retorno

True se os endereços dos objetos coincidirem e false caso contrário.

## Object::ReferenceEquals(T const\&, std::nullptr_t) método


Compara por referência objeto de tipo valor com nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo do objeto a comparar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | T const\& | Primeiro objeto a comparar. |

### Valor de Retorno

Sempre retorna false, pois tipos valor não podem ser nulos.

## Veja Também

* Typedef [ptr](../ptr/)
* Class [String](../../string/)
* Class [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)