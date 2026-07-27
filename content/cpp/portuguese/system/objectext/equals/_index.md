---
title: Equals()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 14
url: /pt/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) método




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) método


Substituição para chamadas C# [Object.Equals](../../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para tipos de ponteiro inteligente.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo do primeiro objeto. |
| T2 | Tipo do segundo objeto. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Primeiro objeto. |
| another | const T2\& | Segundo objeto. |

### Valor de retorno

Verdadeiro se os objetos forem considerados iguais, falso caso contrário.

## ObjectExt::Equals(T, const T2\&) método


Substituição para chamadas C# [Object.Equals](../../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para tipos de estrutura.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo do primeiro objeto. |
| T2 | Tipo do segundo objeto. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | Primeiro objeto. |
| another | const T2\& | Segundo objeto. |

### Valor de retorno

Verdadeiro se os objetos forem considerados iguais, falso caso contrário.

## ObjectExt::Equals(const T\&, const T2\&) método


Substituição para chamadas C# [Object.Equals](../../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para tipos escalares.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo do primeiro objeto. |
| T2 | Tipo do segundo objeto. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Primeiro objeto. |
| another | const T2\& | Segundo objeto. |

### Valor de retorno

Verdadeiro se os objetos forem considerados iguais, falso caso contrário.

## ObjectExt::Equals(const char_t(&), String) método


Substituição para chamadas C# [Object.Equals](../../object/equals/) que funcionam para qualquer tipo em C++. Sobrecarga para literal de string com comparação de strings.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| N | [String](../../string/) tamanho do literal. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Valor de retorno

Verdadeiro se as strings coincidirem, falso caso contrário.

## ObjectExt::Equals(const float\&, const float\&) método


Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **float**\& | Valor de ponto flutuante à esquerda. |
| another | const **float**\& | Valor de ponto flutuante à direita. |

### Valor de retorno

Verdadeiro se **obj** e **another** forem ambos NaN ou iguais, falso caso contrário.

## ObjectExt::Equals(const double\&, const double\&) método


Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **double**\& | Valor de ponto flutuante à esquerda. |
| another | const **double**\& | Valor de ponto flutuante à direita. |

### Valor de retorno

Verdadeiro se **obj** e **another** forem ambos NaN ou iguais, falso caso contrário.

## See Also

* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Estrutura [IsExceptionWrapper](../../isexceptionwrapper/)
* Estrutura [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)