---
title: IPieSplitCustomPointCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa uma coleção de pontos que devem ser desenhados na segunda fatia ou barra de um gráfico de barra-em-pizza ou pizza-em-pizza com uma divisão personalizada.
type: docs
url: /pt/com.aspose.slides/ipiesplitcustompointcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Representa uma coleção de pontos que devem ser desenhados no segundo segmento de pizza ou barra em um gráfico de barra-em-pizza ou pizza-em-pizza com uma divisão personalizada.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna o ponto de dados do gráfico por índice. |
| [add(int dataPointIndex)](#add-int-) | Adiciona ponto de dados pelo seu índice na coleção de pontos da série pai. |
| [remove(int dataPointIndex)](#remove-int-) | Remove item da coleção pelo seu índice na coleção de pontos da série pai. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Retorna o ponto de dados do gráfico por índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do ponto de dados. |

**Retorna:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Ponto de dados do gráfico.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Adiciona ponto de dados pelo seu índice na coleção de pontos da série pai.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPointIndex | int | Índice do ponto de dados na coleção de pontos da série pai. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Remove item da coleção pelo seu índice na coleção de pontos da série pai.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| dataPointIndex | int | Índice do ponto de dados na coleção de pontos da série pai.. |