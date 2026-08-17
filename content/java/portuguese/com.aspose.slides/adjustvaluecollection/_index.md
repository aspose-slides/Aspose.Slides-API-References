---
title: AdjustValueCollection
second_title: Referência da API Aspose.Slides for Java
description: Representa uma coleção de ajustes de formas.
type: docs
url: /pt/com.aspose.slides/adjustvaluecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Representa uma coleção de ajustes de forma.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Return a number of adjustments. |
| [get_Item(int index)](#get-Item-int-) | Returns adjustment by index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
### size() {#size--}
```
public final int size()
```


Retorna um número de ajustes. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```


Retorna o ajuste por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | índice do ajuste. |

**Retorna:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para a matriz especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz alvo. |
| index | int | Índice inicial na matriz alvo. |

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
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```


Retorna um enumerador para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.IEnumerator