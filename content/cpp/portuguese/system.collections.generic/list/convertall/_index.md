---
title: ConvertAll()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma lista de elementos convertidos para um tipo diferente.
type: docs
weight: 352
url: /pt/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) método


Cria uma lista de elementos convertidos para um tipo diferente.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| OutputType | Tipo do elemento da lista de saída. |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Conversor a ser usado para a conversão de itens. |

### Valor de retorno

Uma lista recém-criada de elementos convertidos.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Classe [List](../)
* Espaço de nomes [System::Collections::Generic](../../)
* Biblioteca [Aspose.Slides](../../../)