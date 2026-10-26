---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una colección de puntos para dividir un punto en un gráfico de barra de pastel o pastel dentro de pastel con una división personalizada.
type: docs
url: /es/com.aspose.slides/piesplitcustompointcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Representa una colección de puntos para dividir un punto en un gráfico de barra de pastel o pastel dentro de pastel con una división personalizada.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el punto de datos del gráfico para el índice especificado. |
| [add(int dataPointIndex)](#add-int-) | Añade un punto de datos por su índice en la colección de puntos de la serie principal. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Añade un punto de datos a la colección. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Elimina un elemento de la colección. |
| [remove(int dataPointIndex)](#remove-int-) | Elimina un elemento de la colección por su índice en la colección de puntos de la serie principal. |
| [clear()](#clear--) | Elimina todos los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [size()](#size--) | Devuelve o establece el recuento de puntos de datos del gráfico. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Devuelve el punto de datos del gráfico para el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - punto de datos del gráfico.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Añade un punto de datos por su índice en la colección de puntos de la serie principal.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPointIndex | int | Índice del punto de datos en la colección de puntos de la serie principal. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Añade un punto de datos a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Punto de datos a añadir. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Elimina un elemento de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Punto de datos a eliminar. |

**Devuelve:**
boolean - true si el elemento se elimina correctamente; de lo contrario, false. Este método también devuelve false si el elemento no se encontró en System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Elimina un elemento de la colección por su índice en la colección de puntos de la serie principal.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPointIndex | int | Índice del punto de datos en la colección de puntos de la serie principal. |
### clear() {#clear--}
```
public final void clear()
```

Elimina todos los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection).
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Determina si [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | El objeto a localizar en [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si el elemento se encuentra en [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a una matriz, comenzando en un índice de matriz específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | La matriz unidimensional que es el destino de los elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). La matriz debe tener índices basados en cero. |
| arrayIndex | int | El índice basado en cero en la matriz donde comienza la copia. |
### size() {#size--}
```
public final int size()
```

Devuelve o establece el recuento de puntos de datos del gráfico. int de solo lectura.

**Devuelve:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene un valor que indica si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. boolean de solo lectura.

**Devuelve:**
boolean - true si [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura; de lo contrario, false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). boolean de solo lectura.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Object de solo lectura.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - un java.util.Iterator para toda la colección.