---
title: ColorOperationCollection
second_title: Aspose.Slides para Android via referência da API Java
description: Representa uma coleção de operações de transformação de cores.
type: docs
url: /pt/com.aspose.slides/coloroperationcollection/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Representa uma coleção de operações de transformação de cores.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna o número de operações em uma coleção. |
| [get_Item(int index)](#get-Item-int-) | Retorna ou define a operação no índice especificado. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Retorna ou define a operação no índice especificado. |
| [add(int operation, float parameter)](#add-int-float-) | Adiciona uma nova operação ao final da coleção. |
| [add(int operation)](#add-int-) | Adiciona uma nova operação ao final da coleção. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Insere a nova operação em uma coleção. |
| [insert(int position, int operation)](#insert-int-int-) | Insere a nova operação em uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a operação de cor de uma coleção. |
| [clear()](#clear--) | Remove todas as operações de cor. |
| [iterator()](#iterator--) | Retorna um enumerador que percorre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para a coleção inteira. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. |
| [deepClone()](#deepClone--) | Cria uma cópia de uma coleção ColorOperationCollection. |
| [cloneT()](#cloneT--) | Clona o objeto atual |

### size() {#size--}
```
public final int size()
```

Retorna o número de operações em uma coleção. Somente leitura int.

**Retorna:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Retorna ou define a operação no índice especificado. Leitura/gravação [ColorOperation](../../com.aspose.slides/coloroperation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Retorna ou define a operação no índice especificado. Leitura/gravação [ColorOperation](../../com.aspose.slides/coloroperation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Adiciona uma nova operação ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operation | int | Tipo de operação. |
| parameter | float | Parâmetro da operação. |

**Retorna:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operação adicionada.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Adiciona uma nova operação ao final da coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operation | int | Tipo de operação. |

**Retorna:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operação adicionada.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Insere a nova operação em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | int | O índice onde a operação será inserida. |
| operation | int | Tipo de operação. |
| parameter | float | Parâmetro da operação. |

**Retorna:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operação inserida.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Insere a nova operação em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| position | int | O índice onde a operação será inserida. |
| operation | int | Tipo de operação. |

**Retorna:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Operação inserida.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Remove a operação de cor de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma operação de cor a ser removida. |

### clear() {#clear--}
```
public final void clear()
```

Remove todas as operações de cor.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Retorna um enumerador que percorre a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Um IGenericEnumerator que pode ser usado para percorrer a coleção.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Um java.util.Iterator para a coleção inteira.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

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

Retorna a raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Cria uma cópia de uma coleção ColorOperationCollection.

**Retorna:**
java.lang.Object - Nova [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) coleção.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Clona o objeto atual

**Retorna:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clone