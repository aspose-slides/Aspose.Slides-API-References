---
title: PointCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de pontos de animação.
type: docs
url: /pt/com.aspose.slides/pointcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Representa a coleção de pontos de animação.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Returns the number of points in the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns a point at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Retorna o número de pontos na coleção. int somente leitura.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Retorna um ponto no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[IPoint](../../com.aspose.slides/ipoint) - O objeto [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Retorna um java iterator para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Um java.util.Iterator para toda a coleção.