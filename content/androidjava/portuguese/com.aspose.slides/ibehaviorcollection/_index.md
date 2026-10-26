---
title: IBehaviorCollection
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa uma coleção de efeitos de comportamento.
type: docs
url: /pt/com.aspose.slides/ibehaviorcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Representa uma coleção de efeitos de comportamento.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna um comportamento no índice especificado. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Retorna um comportamento no índice especificado. |
| [getCount()](#getCount--) | Retorna o número de comportamentos em uma coleção. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Adiciona um novo comportamento a uma coleção. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina o índice de um item específico na Lista. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Insere um novo comportamento em uma coleção no índice especificado. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Remove o comportamento especificado de uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove o comportamento de uma coleção no índice especificado. |
| [clear()](#clear--) | Remove todos os comportamentos de uma coleção. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
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
public abstract void set_Item(int index, IBehavior value)
```

Retorna um comportamento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um comportamento a ser retornado. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Retorna o número de comportamentos em uma coleção. Somente leitura int.

**Retorna:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Adiciona um novo comportamento a uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento a ser adicionado. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Determina o índice de um item específico na Lista.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | O objeto a localizar na Lista. |

**Retorna:**
int - O índice do item se encontrado na lista; caso contrário, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Insere um novo comportamento em uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice onde o novo comportamento deve ser inserido. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento a ser inserido. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Remove o comportamento especificado de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento a ser removido. |

**Retorna:**
boolean - Verdadeiro se um comportamento foi removido com sucesso boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o comportamento de uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um comportamento a ser removido. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os comportamentos de uma coleção.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | O objeto a localizar no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - verdadeiro se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, falso.