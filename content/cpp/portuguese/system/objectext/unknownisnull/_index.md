---
title: UnknownIsNull()
second_title: Referência da API Aspose.Slides para C++
description: Verifica se o objeto de tipo desconhecido é nullptr. Sobrecarga para tipos não escalares.
type: docs
weight: 144
url: /pt/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) método


Verifica se o objeto de tipo desconhecido é nullptr. Sobrecarga para tipos não escalares.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### Valor de retorno

True se 'obj == nullptr' for true, false caso contrário.

## ObjectExt::UnknownIsNull(T) método


Verifica se o objeto de tipo desconhecido é nullptr. Sobrecarga para tipos escalares.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | [Object](../../object/) type. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | T | [Object](../../object/) to check. |

### Valor de retorno

Sempre retorna false.

## Veja Também

* Classe [ObjectExt](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)