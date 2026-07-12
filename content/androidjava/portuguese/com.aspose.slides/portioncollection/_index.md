---
title: PortionCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de porções.
type: docs
url: /pt/com.aspose.slides/portioncollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Representa uma coleção de portions.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [isReadOnly()](#isReadOnly--) | Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Obtém o elemento no índice especificado. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Adiciona um Portion ao final da coleção. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina o índice de um item específico na List. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Insere um Portion na coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera pela coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para a coleção inteira. |
### getCount() {#getCount--}
```
public final int getCount()
```

Obtém o número de elementos realmente contidos na coleção. int somente leitura.

**Retorna:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtém um valor que indica se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. boolean somente leitura.

**Retorna:**
boolean - true se o [IGenericCollection](../../com.aspose.slides/igenericcollection) for somente leitura; caso contrário, false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

Adiciona um Portion ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | O Portion a ser adicionado ao final da coleção. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

Determina o índice de um item específico na List.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | O objeto a ser localizado na List. |

**Retorna:**
int - O índice do item se encontrado na lista; caso contrário, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

Insere um Portion na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual o Portion deve ser inserido. |
| value | [IPortion](../../com.aspose.slides/iportion) | O Portion a ser inserido. |
### clear() {#clear--}
```
public final void clear()
```

Remove todos os elementos da coleção.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | O objeto a ser localizado no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - true se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | O Array unidimensional que é o destino dos elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). O Array deve ter indexação baseada em zero. |
| arrayIndex | int | O índice baseado em zero no array onde a cópia começa. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | O objeto a ser removido do [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - true se o item foi removido com sucesso do [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, false. Este método também retorna false se o item não for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection) original.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

Retorna um enumerador que itera pela coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Um IGenericEnumerator que pode ser usado para iterar pela coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

Retorna um iterator java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - Um java.util.Iterator para a coleção inteira.