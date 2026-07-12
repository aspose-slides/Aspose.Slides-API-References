---
title: IColorOperationCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de operações de transformação de cor.
type: docs
url: /pt/com.aspose.slides/icoloroperationcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Representa uma coleção de operações de transformação de cor.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna ou define a operação no índice especificado. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Retorna ou define a operação no índice especificado. |
| [add(int operation, float parameter)](#add-int-float-) | Adiciona uma nova operação ao final da coleção. |
| [add(int operation)](#add-int-) | Adiciona uma nova operação ao final da coleção. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Insere a nova operação em uma coleção. |
| [insert(int position, int operation)](#insert-int-int-) | Insere a nova operação em uma coleção. |
| [removeAt(int index)](#removeAt-int-) | Remove a operação de cor de uma coleção. |
| [clear()](#clear--) | Remove todas as operações de cor. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Retorna ou define a operação no índice especificado. Leitura/gravação [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Retorna ou define a operação no índice especificado. Leitura/gravação [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
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
public abstract IColorOperation add(int operation)
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
public abstract IColorOperation insert(int position, int operation, float parameter)
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
public abstract IColorOperation insert(int position, int operation)
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
public abstract void removeAt(int index)
```

Remove a operação de cor de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma operação de cor a ser removida. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todas as operações de cor.