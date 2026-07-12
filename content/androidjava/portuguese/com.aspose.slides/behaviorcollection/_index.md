---
title: BehaviorCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de efeitos de comportamento.
type: docs
url: /pt/com.aspose.slides/behaviorcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Representa uma coleção de efeitos de comportamento.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Retorna o número de comportamentos em uma coleção. |
| [isReadOnly()](#isReadOnly--) | Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Adiciona um novo comportamento a uma coleção. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina o índice de um item específico na Lista. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Insere um novo comportamento em uma coleção no índice especificado. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Remove o comportamento especificado de uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o comportamento de uma coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os comportamentos de uma coleção. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [get_Item(int index)](#get-Item-int-) | Retorna um comportamento no índice especificado. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Define um comportamento no índice especificado. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
### getCount() {#getCount--}
```
public final int getCount()
```

Retorna o número de comportamentos em uma coleção. Somente leitura int.

**Retorna:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. Somente leitura boolean.

**Retorna:**
boolean - verdadeiro se o [IGenericCollection](../../com.aspose.slides/igenericcollection) for somente leitura; caso contrário, falso.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

Adiciona um novo comportamento a uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento a ser adicionado. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

Determina o índice de um item específico na Lista.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | O objeto a ser localizado na Lista. |

**Retorna:**
int - O índice do item se encontrado na lista; caso contrário, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

Insere um novo comportamento em uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice onde o novo comportamento deve ser inserido. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento a ser inserido. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | O Array unidimensional que é o destino dos elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). O Array deve ter indexação baseada em zero. |
| arrayIndex | int | O índice baseado em zero no array a partir do qual a cópia começa. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

Remove o comportamento especificado de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento a ser removido. |

**Retorna:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o comportamento de uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um comportamento a ser removido. |
### clear() {#clear--}
```
public final void clear()
```

Remove todos os comportamentos de uma coleção.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | O objeto a ser localizado no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

Retorna um comportamento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um comportamento a ser retornado. |

**Retorna:**
[IBehavior](../../com.aspose.slides/ibehavior) - Comportamento de animação.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

Define um comportamento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um comportamento a ser retornado. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - An java.util.Iterator for the entire collection.