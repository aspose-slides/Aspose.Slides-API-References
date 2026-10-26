---
title: ExtraColorSchemeCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de esquemas de cores adicionais.
type: docs
url: /pt/com.aspose.slides/extracolorschemecollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Representa uma coleção de esquemas de cores adicionais.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna um número de elementos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna um esquema de cor por índice. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para a matriz especificada. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso ao ArrayList está sincronizado (seguro para threads). |
| [getSyncRoot()](#getSyncRoot--) | Retorna um objeto que pode ser usado para sincronizar o acesso à coleção. |
### size() {#size--}
```
public final int size()
```

Retorna um número de elementos na coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Retorna um esquema de cor por índice. Somente leitura [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retorna objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Retorna um enumerador que itera sobre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para a matriz especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz de destino. |
| index | int | Índice inicial na matriz. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso ao ArrayList está sincronizado (seguro para threads). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna um objeto que pode ser usado para sincronizar o acesso à coleção. Somente leitura Object.

Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object