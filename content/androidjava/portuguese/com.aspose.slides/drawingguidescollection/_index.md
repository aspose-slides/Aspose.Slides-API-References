---
title: DrawingGuidesCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção dos guias de desenho ajustáveis.
type: docs
url: /pt/com.aspose.slides/drawingguidescollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Representa uma coleção dos guias de desenho ajustáveis.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o guia de desenho por índice. |
| [add(byte orientation, float position)](#add-byte-float-) | Adiciona o guia de desenho ao final da coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o guia de desenho no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [getCount()](#getCount--) | Retorna o número de elementos na coleção. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Copies all elements from the collection to the specified array. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Retorna o guia de desenho por índice. Somente leitura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Adiciona o guia de desenho ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| orientation | byte | Orientação do guia de desenho. |
| position | float | Posição do guia de desenho em pontos. |

**Retorna:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove o guia de desenho no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do guia de desenho que deve ser excluído. |

### clear() {#clear--}
```
public final void clear()
```


Remove todos os elementos da coleção.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Um java.util.Iterator para toda a coleção.
### getCount() {#getCount--}
```
public final int getCount()
```


Retorna o número de elementos na coleção. Somente leitura int.

**Retorna:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Array de destino. |
| index | int | Índice inicial no array de destino. |