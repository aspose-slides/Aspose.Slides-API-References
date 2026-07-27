---
title: Unbox()
second_title: Referência da API Aspose.Slides para C++
description: Desempacota tipos de valor após converter para Object. Implementação para tipos enum.
type: docs
weight: 53
url: /pt/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempacota tipos de valor após converter para [Object](../../object/). Implementação para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempacotar. |

### Valor de Retorno

[Enum](../../enum/) valor.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempacota tipos de valor após converter para [Object](../../object/). Implementação para tipos que não são enum e não são anuláveis.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempacotar. |

### Valor de Retorno

Valor desempacotado.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempacota tipos de valor após converter para [Object](../../object/). Implementação para tipos que não são enum e não são anuláveis.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempacotar. |

### Valor de Retorno

Valor desempacotado.

## ObjectExt::Unbox(E) método


Desempacota tipos enum para inteiro.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo inteiro de destino. |
| E | Tipo enum de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| e | E | Valor a desempacotar. |

### Valor de Retorno

Representação inteira do enum.

## ObjectExt::Unbox(E) método


Converte tipos enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo enum de destino. |
| E | Tipo enum de origem. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| e | E | Valor a desempacotar. |

### Valor de Retorno

Valor enum convertido.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) método


Desempacota valores de string.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) para desempacotar |

### Valor de Retorno

[String](../../string/) representação da string empacotada, pode ser nula se a string empacotada for nula.

## Veja Também

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)