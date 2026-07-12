---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de objetos GradientStopData.
type: docs
url: /pt/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

Representa uma coleção de objetos GradientStopData.

## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Returns the number of gradient stops in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the gradient stop by index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |

### size() {#size--}
```
public final int size()
```

Retorna o número de pontos de gradiente em uma coleção. Somente leitura int.

**Retorna:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

Retorna o ponto de gradiente por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para a matriz especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz de destino. |
| index | int | Índice inicial na matriz de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object