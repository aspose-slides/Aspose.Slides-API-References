---
title: CellCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de células.
type: docs
url: /pt/com.aspose.slides/cellcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

Representa uma coleção de células.
## Métodos

| Método | Descrição |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | Retorna o número de células em uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna uma célula pela sua posição. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para a coleção inteira. |
| [getSlide()](#getSlide--) | Retorna o slide pai de um CellCollection. |
| [getPresentation()](#getPresentation--) | Retorna a apresentação pai de um CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


Retorna o número de células em uma coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


Retorna uma célula pela sua posição. Somente leitura [Cell](../../com.aspose.slides/cell).

--------------------

Um objeto Cell pode ser retornado para vários índices caso a célula esteja mesclada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


Retorna um iterator java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - Um java.util.Iterator para a coleção inteira.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retorna o slide pai de um CellCollection. Somente leitura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retorna:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retorna a apresentação pai de um CellCollection. Somente leitura [IPresentation](../../com.aspose.slides/ipresentation).

**Retorna:**
[IPresentation](../../com.aspose.slides/ipresentation)
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


Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object