---
title: IChartSeriesGroupCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa a coleção de grupos de séries combináveis.
type: docs
url: /pt/com.aspose.slides/ichartseriesgroupcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesGroupCollection extends IGenericCollection<IChartSeriesGroup>
```

Representa a coleção de grupos de séries combináveis.

--------------------

1) Cada grupo de séries contém séries com tipos combináveis. Grupos de tipos de séries combináveis são definidos e descritos com o enum CombinableSeriesTypesGroup. Também cada grupo de séries contém séries que são plotadas nos eixos primários ou nos eixos secundários (não ambos os casos em um mesmo grupo). Portanto, o princípio de agrupamento de séries é um agrupamento pelos grupos de tipos mencionados acima e pelo tipo de plotagem primário/secundário. 2) O grupo de séries contém algumas propriedades de séries que são comuns a cada série no grupo (“propriedades do grupo de séries”). “Propriedades do grupo de séries” na classe ChartSeriesGroup são leitura/gravação. Cada “propriedade do grupo de séries” pode ter uma projeção somente leitura na classe ChartSeries.

## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(IChartSeries ofSeries)](#get-Item-com.aspose.slides.IChartSeries-) | Obtém o grupo de séries por série. |
| [get_Item(int index)](#get-Item-int-) | Obtém o grupo de séries por índice. |
### get_Item(IChartSeries ofSeries) {#get-Item-com.aspose.slides.IChartSeries-}
```
public abstract IChartSeriesGroup get_Item(IChartSeries ofSeries)
```


Obtém o grupo de séries por série.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| ofSeries | [IChartSeries](../../com.aspose.slides/ichartseries) |  |

**Retorna:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeriesGroup get_Item(int index)
```


Obtém o grupo de séries por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)