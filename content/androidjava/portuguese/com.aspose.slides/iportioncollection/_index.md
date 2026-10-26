---
title: IPortionCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de porções.
type: docs
url: /pt/com.aspose.slides/iportioncollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Representa uma coleção de porções.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getCount()](#getCount--) | Obtém o número de elementos realmente contidos na coleção. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Adiciona um Portion ao final da coleção. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina o índice de uma porção específica na coleção. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Insere um Portion na coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtém o número de elementos realmente contidos na coleção. int somente leitura.

**Retorna:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


Adiciona um Portion ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | A Portion a ser adicionada ao final da coleção. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


Determina o índice de uma porção específica na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | A porção a ser localizada na coleção. |

**Retorna:**
int - O índice do item se encontrado na coleção; caso contrário, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


Insere um Portion na coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero no qual o Portion deve ser inserido. |
| value | [IPortion](../../com.aspose.slides/iportion) | O Portion a ser inserido. |

### clear() {#clear--}
```
public abstract void clear()
```


Remove todos os elementos da coleção.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | O objeto a ser localizado no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | O objeto a ser removido do [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item foi removido com sucesso do [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso. Este método também retorna falso se o item não for encontrado na [IGenericCollection](../../com.aspose.slides/igenericcollection) original.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Remove o elemento no índice especificado da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |