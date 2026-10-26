---
title: Clear()
second_title: Referência da API Aspose.Slides para C++
description: Não suportado porque o array representado pelo objeto atual é somente leitura.
type: docs
weight: 53
url: /pt/system/array/clear/
---
## Array::Clear() método


Não suportado porque o array representado pelo objeto atual é somente leitura.

```cpp
virtual void System::Array<T>::Clear() override
```


## Array::Clear(const ArrayPtr\<Type\>\&, int, int) método


Substitui **count** valores a partir do índice **startIndex** no array especificado por valores padrão.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```


### Parâmetros do modelo

| Parâmetro | Descrição |
| --- | --- |
| Type | Tipo de elementos no array de destino |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Array de destino |
| startIndex | int | [Index](../../index/) no qual começar a substituir os itens |
| count | int | O número de itens a substituir |

## Ver também

* Typedef [ArrayPtr](../../arrayptr/)
* Method [Type](../../object/type/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)