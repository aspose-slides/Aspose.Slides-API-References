---
title: TrendlineCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de Trendline
type: docs
url: /pt/com.aspose.slides/trendlinecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Representa uma coleção de Trendline
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [add(int trendlineType)](#add-int-) | Adiciona a nova Trendline ao final de uma coleção e a retorna. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Remove o valor especificado. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [Trendline](../../com.aspose.slides/trendline).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


Adiciona a nova Trendline ao final de uma coleção e a retorna.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| trendlineType | int |  |

**Retorno:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```


Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


Retorna um iterador java para a coleção inteira.

**Retorno:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorno:**
int