---
title: IChartSeriesCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de
type: docs
url: /pt/com.aspose.slides/ichartseriescollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Representa a coleção de [IChartSeries](../../com.aspose.slides/ichartseries)
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [add(int type)](#add-int-) | Cria uma nova série de gráfico e a adiciona à coleção. |
| [insert(int index, int type)](#insert-int-int-) | Cria uma nova série de gráfico e a insere na coleção. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Cria uma nova série de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) e a adiciona à coleção. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Cria uma nova série de gráfico a partir de [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) e a adiciona à coleção. |
| [add(String name, int type)](#add-java.lang.String-int-) | Cria uma nova série de gráfico a partir de valor e a adiciona à coleção. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Pesquisa o [IChartSeries](../../com.aspose.slides/ichartseries) especificado e retorna o índice baseado em zero da primeira ocorrência em toda a Coleção |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Remove o valor especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado |
| [clear()](#clear--) | Remove todos os elementos (incluindo o estilo do gráfico) da coleção. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - O elemento no índice especificado.

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Cria uma nova série de gráfico e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | int | Tipo da série |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nova série de gráfico.

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Cria uma nova série de gráfico e a insere na coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice para inserção |
| type | int | Tipo de gráfico [ChartType](../../com.aspose.slides/charttype) |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nova série de gráfico [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Cria uma nova série de gráfico a partir de [IChartDataCell](../../com.aspose.slides/ichartdatacell) e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Célula que contém o nome da série. |
| type | int | Tipo define o tipo da série

--------------------
Se a série de gráfico for criada a partir da mesma célula que já está na coleção, então o método não adiciona nada e retorna seu índice. |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de gráfico adicionada ou série que já está na coleção.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Cria uma nova série de gráfico a partir de [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Células que contêm o nome da série. |
| type | int | Tipo define o tipo da série

--------------------
Se a série de gráfico for criada a partir da mesma célula que já está na coleção, então o método não adiciona nada e retorna seu índice. |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de gráfico adicionada ou série que já está na coleção.

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Cria uma nova série de gráfico a partir de valor e a adiciona à coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| name | java.lang.String | Nome da série. |
| type | int | Tipo define o tipo da série |

**Retorna:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Série de gráfico adicionada.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Pesquisa o [IChartSeries](../../com.aspose.slides/ichartseries) especificado e retorna o índice baseado em zero da primeira ocorrência em toda a Collection

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Valor da série de gráfico. |

**Retorna:**
int - O índice baseado em zero da primeira ocorrência do valor em toda a CollectionBase, se encontrado; caso contrário, -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Remove o valor especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | O valor. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice |

### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os elementos (incluindo o estilo do gráfico) da coleção.