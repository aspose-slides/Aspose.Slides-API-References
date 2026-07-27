---
title: Box()
second_title: Referência da API Aspose.Slides para C++
description: Empacota tipos de valor para conversão para Object. Implementação para tipos enum.
type: docs
weight: 40
url: /pt/system/objectext/box/
---
## ObjectExt::Box(const T\&) método


Empacota tipos de valor para conversão para [Object](../../object/). Implementação para tipos enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) tipo. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) valor a empacotar. |

### Valor de retorno

Ponteiro inteligente para objeto que mantém o valor empacotado.

## ObjectExt::Box(const T\&) método


Empacota tipos de valor para conversão para [Object](../../object/). Implementação para tipos não-enum.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Valor a empacotar. |

### Valor de retorno

Ponteiro inteligente para objeto que mantém o valor empacotado.

## ObjectExt::Box(const T\&) método


Empacota tipos [Nullable](../../nullable/) para conversão para [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Tipo de valor. |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Valor a empacotar. |

### Valor de retorno

Ponteiro inteligente para objeto que mantém o valor empacotado.

## ObjectExt::Box(const String\&) método


Empacota valores de string.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Valor a empacotar. |

### Valor de retorno

Valor empacotado ou null, se a string de origem for null.

## Veja também

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Classe [String](../../string/)
* Estrutura [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)