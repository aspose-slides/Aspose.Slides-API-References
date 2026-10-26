---
title: Equals()
second_title: Referência da API Aspose.Slides para C++
description: Compara objetos usando a semântica C# Object.Equals.
type: docs
weight: 157
url: /pt/system/object/equals/
---
## Object::Equals(ptr) método


Compara objetos usando semântica C# [Object.Equals](./).

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) para comparar o atual. |

### Valor de retorno

True se objetos são considerados iguais e false caso contrário.

## Object::Equals(T1 const\&, T2 const\&) método


Compara objetos de tipo referência no estilo C#.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do primeiro objeto a comparar. |
| T2 | Tipo do segundo objeto a comparar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | T1 const\& | Primeiro objeto a comparar. |
| objB | T2 const\& | Segundo objeto a comparar. |

### Valor de retorno

True se os objetos coincidirem por referência ou semanticamente (por comparação semelhante a [Object.Equals](./)), false caso contrário.

## Object::Equals(T1 const\&, T2 const\&) método


Compara objetos de tipo valor no estilo C#.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T1 | Tipo do primeiro objeto a comparar. |
| T2 | Tipo do segundo objeto a comparar. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | T1 const\& | Primeiro objeto a comparar. |
| objB | T2 const\& | Segundo objeto a comparar. |

### Valor de retorno

True se os objetos forem considerados iguais pelo operador de igualdade disponível, false caso contrário.

## Object::Equals(float const\&, float const\&) método


Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | **float** const\& | Valor de ponto flutuante do lado esquerdo. |
| objB | **float** const\& | Valor de ponto flutuante do lado direito. |

### Valor de retorno

True se **objA** e **objB** forem ambos NaN ou iguais, false caso contrário.

## Object::Equals(double const\&, double const\&) método


Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| objA | **double** const\& | Valor de ponto flutuante do lado esquerdo. |
| objB | **double** const\& | Valor de ponto flutuante do lado direito. |

### Valor de retorno

True se **objA** e **objB** forem ambos NaN ou iguais, false caso contrário.

## Veja também

* Typedef [ptr](../ptr/)
* Classe [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* namespace [System](../../)
* Library [Aspose.Slides](../../../)