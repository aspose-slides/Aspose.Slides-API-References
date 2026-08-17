---
title: SequenceCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa coleção de sequências interativas.
type: docs
url: /pt/com.aspose.slides/sequencecollection/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Representa coleção de sequências interativas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Retorna o número de elementos em uma coleção Somente leitura int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Adiciona nova sequência interativa. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Remove a sequência especificada de uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a sequência no índice especificado. |
| [clear()](#clear--) | Remove todas as sequências de uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna uma sequência no índice especificado. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
### getCount() {#getCount--}
```
public final int getCount()
```

Retorna o número de elementos em uma coleção Somente leitura int.

**Retorna:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

Adiciona nova sequência interativa. Leitura/gravação [Sequence](../../com.aspose.slides/sequence).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Retorna:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

Remove a sequência especificada de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequência a ser removida. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove a sequência no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da sequência que deve ser deletada. |

### clear() {#clear--}
```
public final void clear()
```

Remove todas as sequências de uma coleção.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

Retorna uma sequência no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[ISequence](../../com.aspose.slides/isequence) - O objeto [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - Um java.util.Iterator para a coleção inteira.