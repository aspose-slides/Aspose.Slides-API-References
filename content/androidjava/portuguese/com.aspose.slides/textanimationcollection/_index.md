---
title: TextAnimationCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de animações de texto.
type: docs
url: /pt/com.aspose.slides/textanimationcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

Representa uma coleção de animações de texto.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna um número de elementos na coleção. |
| [add()](#add--) | Adiciona nova animação de texto à coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna o elemento por índice. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Retorna todos os elementos |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para toda a coleção. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


Retorna um número de elementos na coleção. Somente leitura int.

**Retorna:**
int
### add() {#add--}
```
public final TextAnimation add()
```


Adiciona nova animação de texto à coleção.

**Retorna:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


Retorna o elemento por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


Retorna todos os elementos

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) para remover. |

**Retorna:**
com.aspose.slides.ITextAnimation[] - Array de [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


Retorna um iterator java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - Um java.util.Iterator para toda a coleção.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array a ser preenchido. |
| index | int | Posição inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna uma raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object