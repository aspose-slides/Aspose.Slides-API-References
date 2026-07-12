---
title: DataLabelFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de formatação para DataLabel.
type: docs
url: /pt/com.aspose.slides/datalabelformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Representa opções de formatação para DataLabel.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Leitura/gravação boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Leitura/gravação boolean. |
| [getNumberFormat()](#getNumberFormat--) | Representa a string de formato para o objeto DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa a string de formato para o objeto DataLabels. |
| [getFormat()](#getFormat--) | Representa o formato do rótulo de dados. |
| [getPosition()](#getPosition--) | Representa a posição do rótulo de dados. |
| [setPosition(int value)](#setPosition-int-) | Representa a posição do rótulo de dados. |
| [getShowLegendKey()](#getShowLegendKey--) | Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. |
| [getShowValue()](#getShowValue--) | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. |
| [getShowCategoryName()](#getShowCategoryName--) | Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. |
| [getShowSeriesName()](#getShowSeriesName--) | Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. |
| [getShowPercentage()](#getShowPercentage--) | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representa o comportamento de exibição do valor de tamanho da bolha do rótulo de dados de um gráfico especificado. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representa o comportamento de exibição do valor de tamanho da bolha do rótulo de dados de um gráfico especificado. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representa o comportamento de exibição das linhas guia do rótulo de dados de um gráfico especificado. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representa o comportamento de exibição das linhas guia do rótulo de dados de um gráfico especificado. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados. |
| [getSeparator()](#getSeparator--) | Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. |
| [getTextFormat()](#getTextFormat--) | Retorna o formato de texto do gráfico. |
| [getChart()](#getChart--) | Retorna o gráfico. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade IsNumberFormatLinkedToSource para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade IsNumberFormatLinkedToSource de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" faz com que todos DataLabels.get_Item(i).isNumberFormatLinkedToSource() sejam iguais a val).

**Retorna:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade IsNumberFormatLinkedToSource para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade IsNumberFormatLinkedToSource de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" faz com que todos DataLabels.get_Item(i).isNumberFormatLinkedToSource() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Representa a string de formato para o objeto DataLabels. Leitura/gravação String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade NumberFormat para os novos rótulos de dados na coleção DataLabelCollection. Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" faz com que todos DataLabels.get_Item(i).getNumberFormat() sejam iguais a val).

**Retorna:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Representa a string de formato para o objeto DataLabels. Leitura/gravação String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados, então esta propriedade obtém ou define o valor padrão da propriedade NumberFormat para os novos rótulos de dados na coleção DataLabelCollection. Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" faz com que todos DataLabels.get_Item(i).getNumberFormat() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Representa o formato do rótulo de dados. Somente leitura [IFormat](../../com.aspose.slides/iformat).

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade representa o formato padrão para os novos rótulos de dados na coleção DataLabelCollection.

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Representa a posição do rótulo de dados. Leitura/gravação [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade Position para os novos rótulos de dados na coleção DataLabelCollection. Representa a posição para os objetos DataLabel. Definir esta propriedade com um valor também define esse valor para a propriedade Position de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setPosition(val);" faz com que todos DataLabels.get_Item(i).getPosition() sejam iguais a val).

**Retorna:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Representa a posição do rótulo de dados. Leitura/gravação [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade Position para os novos rótulos de dados na coleção DataLabelCollection. Representa a posição para os objetos DataLabel. Definir esta propriedade com um valor também define esse valor para a propriedade Position de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setPosition(val);" faz com que todos DataLabels.get_Item(i).getPosition() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. Verdadeiro se a chave de legenda do rótulo de dados estiver visível. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLegendKey para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLegendKey de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" faz com que todos DataLabels.get_Item(i).getShowLegendKey() sejam iguais a val).

**Retorna:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Representa o comportamento de exibição da chave de legenda do rótulo de dados de um gráfico especificado. Verdadeiro se a chave de legenda do rótulo de dados estiver visível. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLegendKey para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLegendKey de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" faz com que todos DataLabels.get_Item(i).getShowLegendKey() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowValue para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowValue de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" faz com que todos DataLabels.get_Item(i).getShowValue() sejam iguais a val).

**Retorna:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowValue para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowValue de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" faz com que todos DataLabels.get_Item(i).getShowValue() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. Verdadeiro exibe o nome da categoria. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowCategoryName para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowCategoryName de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" faz com que todos DataLabels.get_Item(i).getShowCategoryName() sejam iguais a val).

**Retorna:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Representa o comportamento de exibição do nome da categoria do rótulo de dados de um gráfico especificado. Verdadeiro exibe o nome da categoria. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowCategoryName para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowCategoryName de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" faz com que todos DataLabels.get_Item(i).getShowCategoryName() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. Verdadeiro exibe o nome da série. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowSeriesName de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" faz com que todos DataLabels.get_Item(i).getShowSeriesName() sejam iguais a val).

**Retorna:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série para os rótulos de dados em um gráfico. Verdadeiro exibe o nome da série. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowSeriesName de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" faz com que todos DataLabels.get_Item(i).getShowSeriesName() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowPercentage para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowPercentage de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" faz com que todos DataLabels.get_Item(i).getShowPercentage() sejam iguais a val).

**Retorna:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Representa o comportamento de exibição do valor percentual do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowPercentage para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowPercentage de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" faz com que todos DataLabels.get_Item(i).getShowPercentage() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Representa o comportamento de exibição do valor de tamanho da bolha do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor da bolha. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowBubbleSize para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowBubbleSize de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" faz com que todos DataLabels.get_Item(i).getShowBubbleSize() sejam iguais a val).

**Retorna:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Representa o comportamento de exibição do valor de tamanho da bolha do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor da bolha. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowBubbleSize para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowBubbleSize de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" faz com que todos DataLabels.get_Item(i).getShowBubbleSize() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Representa o comportamento de exibição das linhas guia do rótulo de dados de um gráfico especificado. Verdadeiro exibe as linhas guia. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLeaderLines para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLeaderLines de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" faz com que todos DataLabels.get_Item(i).getShowLeaderLines() sejam iguais a val).

**Retorna:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Representa o comportamento de exibição das linhas guia do rótulo de dados de um gráfico especificado. Verdadeiro exibe as linhas guia. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLeaderLines para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLeaderLines de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" faz com que todos DataLabels.get_Item(i).getShowLeaderLines() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor da célula. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelValueFromCell para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLabelValueFromCell de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" faz com que todos DataLabels.get_Item(i).getShowLabelValueFromCell() sejam iguais a val).

**Retorna:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Representa o comportamento de exibição do valor da célula do rótulo de dados de um gráfico especificado. Verdadeiro exibe o valor da célula. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelValueFromCell para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLabelValueFromCell de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" faz com que todos DataLabels.get_Item(i).getShowLabelValueFromCell() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelAsDataCallout para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLabelAsDataCallout de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" faz com que todos DataLabels.get_Item(i).getShowLabelAsDataCallout() sejam iguais a val).

**Retorna:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Determina se o rótulo de dados de um gráfico especificado será exibido como chamada de dados ou como rótulo de dados.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelAsDataCallout para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade ShowLabelAsDataCallout de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" faz com que todos DataLabels.get_Item(i).getShowLabelAsDataCallout() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. Leitura/gravação String.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade Separator para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade Separator de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" faz com que todos DataLabels.get_Item(i).getSeparator() sejam iguais a val).

**Retorna:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Define ou retorna um Variant que representa o separador usado para os rótulos de dados em um gráfico. Leitura/gravação String.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de rótulos de dados então esta propriedade obtém ou define o valor padrão da propriedade Separator para os novos rótulos de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor para a propriedade Separator de todos os rótulos de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" faz com que todos DataLabels.get_Item(i).getSeparator() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Retorna o formato de texto do gráfico. Somente leitura [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Retorna:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Retorna o gráfico. Somente leitura [IChart](../../com.aspose.slides/ichart).

**Retorna:**
[IChart](../../com.aspose.slides/ichart)