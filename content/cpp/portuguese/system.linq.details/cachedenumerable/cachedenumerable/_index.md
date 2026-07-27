---
title: CachedEnumerable()
second_title: Referência da API Aspose.Slides para C++
description: 
type: docs
weight: 1
url: /pt/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) construtor




```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | callback que é chamado quando o próximo item é necessário. callback deve usar o método Add para inserir o próximo item ou retornar false quando não houver mais itens |

## Ver também

* Classe [Func](../../../system/func/)
* Classe [CachedEnumerable](../)
* Espaço de nomes [System::Linq::Details](../../)
* Library [Aspose.Slides](../../../)