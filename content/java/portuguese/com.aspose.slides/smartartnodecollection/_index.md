---
title: SmartArtNodeCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de nós SmartArt.
type: docs
url: /pt/com.aspose.slides/smartartnodecollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Representa uma coleção de nós SmartArt.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna nó por índice |
| [size()](#size--) | Retorna a contagem de nós na coleção Read-only  int  Read-only  int . |
| [addNode()](#addNode--) | Adiciona um novo nó smart art ou subnó. |
| [removeNode(int index)](#removeNode-int-) | Remove nó ou subnó por índice |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Remove nó ou subnó |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Adiciona um novo nó na posição selecionada da coleção de nós |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```


Retorna nó por índice

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento |

**Retorna:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - O nó SmartArt
### size() {#size--}
```
public final int size()
```


Retorna a contagem de nós na coleção Read-only  int  Read-only  int .

**Retorna:**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```


Adiciona um novo nó smart art ou subnó.

**Retorna:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nó adicionado
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```


Remove nó ou subnó por índice

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice baseado em zero do nó |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```


Remove nó ou subnó

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nó a ser removido |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```


Adiciona um novo nó na posição selecionada da coleção de nós

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | int | Posição do nó baseada em zero |

**Retorna:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nó adicionado
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```


Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```


Retorna um iterator java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Um java.util.Iterator para toda a coleção.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Read-only  boolean .

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Read-only Object.

**Retorna:**
java.lang.Object