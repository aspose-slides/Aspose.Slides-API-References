---
title: IChartCategoryCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de
type: docs
url: /pt/com.aspose.slides/ichartcategorycollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Representa a coleção de [IChartCategory](../../com.aspose.slides/ichartcategory)
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [getUseCells()](#getUseCells--) | Se true então a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Se true então a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Retorna a contagem dos níveis de agrupamento de categorias usados. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Se a categoria existir na coleção, retorná-la. |
| [add(Object value)](#add-java.lang.Object-) | Cria um novo [IChartCategory](../../com.aspose.slides/ichartcategory) a partir do valor e o adiciona à coleção. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Procura o [IChartCategory](../../com.aspose.slides/ichartcategory) especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Remove o valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice fornecido. |
| [clear()](#clear--) | Remove todos os elementos da coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - O elemento no índice especificado.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Se true então a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). Se false então a planilha NÃO é usada para armazenar valores (e este caso não suporta categorias de múltiplos níveis). Boolean de leitura/gravação.

**Retorna:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Se true então a planilha é usada para armazenar categorias (este caso suporta categorias de múltiplos níveis). Se false então a planilha NÃO é usada para armazenar valores (e este caso não suporta categorias de múltiplos níveis). Boolean de leitura/gravação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Retorna a contagem dos níveis de agrupamento de categorias usados. É maior que um para categorias de múltiplos níveis. int somente leitura.

**Retorna:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Se a categoria existir na coleção, retorne-a. Caso contrário, cria uma nova categoria de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Célula usada para criar a categoria de gráfico. |

**Retorna:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Categoria adicionada ou existente.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Cria um novo [IChartCategory](../../com.aspose.slides/ichartcategory) a partir do valor e o adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Object | O valor.

--------------------

Este método adiciona uma planilha com o nome AUTO_DATA e adiciona todos os valores lá. Se você usar [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) para adicionar ou editar valores de célula, certifique-se de não usar esta planilha. O número máximo de valores adicionados usando este método não deve exceder 16711680 |

**Retorna:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) adicionados.
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Procura o [IChartCategory](../../com.aspose.slides/ichartcategory) especificado e retorna o índice baseado em zero da primeira ocorrência dentro de toda a Collection

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Categoria de gráfico. |

**Retorna:**
int - O índice baseado em zero da primeira ocorrência do valor dentro de toda a CollectionBase, se encontrado; caso contrário, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | O valor. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice fornecido.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de uma categoria a ser removida. |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os elementos da coleção.