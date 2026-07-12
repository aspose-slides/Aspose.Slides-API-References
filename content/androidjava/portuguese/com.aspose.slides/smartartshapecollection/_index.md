---
title: SmartArtShapeCollection
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma coleção de formas SmartArt
type: docs
url: /pt/com.aspose.slides/smartartshapecollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

Representa uma coleção de formas SmartArt
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna um objeto raiz de sincronização. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
### size() {#size--}
```
public final int size()
```

Obtém o número de elementos realmente contidos na coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da forma |

**Retorna:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - A forma SmartArt
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

Retorna um objeto raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object
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

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - A IGenericEnumerator que pode ser usada para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Um java.util.Iterator para a coleção inteira.