---
title: ISequenceCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa uma coleção de sequências interativas.
type: docs
url: /pt/com.aspose.slides/isequencecollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Representa uma coleção de sequências interativas.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Retorna o número de elementos em uma coleção Read-only int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Adiciona nova sequência interativa. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Remove a sequência especificada de uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a sequência no índice especificado. |
| [clear()](#clear--) | Remove todas as sequências de uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna uma sequência no índice especificado. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retorna o número de elementos em uma coleção Read-only int.

**Retorna:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Adiciona nova sequência interativa.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) |

**Retorna:**
[ISequence](../../com.aspose.slides/isequence) - Nova sequência [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Remove a sequência especificada de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequência a remover. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove a sequência no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento na coleção int |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todas as sequências de uma coleção.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Retorna uma sequência no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[ISequence](../../com.aspose.slides/isequence) - O objeto [ISequence](../../com.aspose.slides/isequence).