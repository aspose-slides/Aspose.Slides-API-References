---
title: ISmartArtNodeCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de nós SmartArt.
type: docs
url: /pt/com.aspose.slides/ismartartnodecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Representa uma coleção de nós SmartArt.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o nó pelo índice. |
| [addNode()](#addNode--) | Adiciona um novo nó ou subnó. |
| [removeNode(int index)](#removeNode-int-) | Remove nó ou subnó pelo índice. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Remove nó ou subnó. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Adiciona um novo nó na posição selecionada da coleção de nós. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Retorna o nó pelo índice. Somente leitura [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento. |

**Retorna:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Adiciona um novo nó ou subnó.

**Retorna:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nó adicionado
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Remove nó ou subnó pelo índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice baseado em zero do nó |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Remove nó ou subnó.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nó a ser removido. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Adiciona um novo nó na posição selecionada da coleção de nós.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | int | Posição do nó baseada em zero. |

**Retorna:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nó adicionado