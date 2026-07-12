---
title: SectionSlideCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de slides na seção.
type: docs
url: /pt/com.aspose.slides/sectionslidecollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Representa uma coleção de slides na seção.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia toda a coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```


Obtém o número de elementos realmente contidos na coleção. int somente leitura.

**Retorna:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia toda a coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | Índice no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Object somente leitura.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Um IGenericEnumerator que pode ser usado para iterar sobre a coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Um java.util.Iterator para toda a coleção.