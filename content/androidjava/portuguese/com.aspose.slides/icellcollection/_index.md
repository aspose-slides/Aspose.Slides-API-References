---
title: ICellCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de células.
type: docs
url: /pt/com.aspose.slides/icellcollection/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Representa uma coleção de células.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna uma célula por sua posição. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Retorna uma célula por sua posição. Somente leitura [ICell](../../com.aspose.slides/icell).

--------------------

Um objeto CellEx pode ser retornado para vários índices caso a célula esteja mesclada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[ICell](../../com.aspose.slides/icell)