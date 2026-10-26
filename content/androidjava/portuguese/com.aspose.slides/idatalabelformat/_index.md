---
title: IDataLabelFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de formatação para DataLabel.
type: docs
url: /pt/com.aspose.slides/idatalabelformat/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Representa opções de formatação para DataLabel.
## Métodos

| Método | Descrição |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Leitura/gravação boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Leitura/gravação boolean. |
| [getNumberFormat()](#getNumberFormat--) | Representa a string de formato para o objeto DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Representa a string de formato para o objeto DataLabels. |
| [getFormat()](#getFormat--) | Representa o formato da etiqueta de dados. |
| [getPosition()](#getPosition--) | Representa a posição da etiqueta de dados. |
| [setPosition(int value)](#setPosition-int-) | Representa a posição da etiqueta de dados. |
| [getShowLegendKey()](#getShowLegendKey--) | Representa o comportamento de exibição da chave de legenda da etiqueta de dados de um gráfico especificado. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Representa o comportamento de exibição da chave de legenda da etiqueta de dados de um gráfico especificado. |
| [getShowValue()](#getShowValue--) | Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. |
| [getShowCategoryName()](#getShowCategoryName--) | Representa o comportamento de exibição do nome da categoria da etiqueta de dados de um gráfico especificado. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Representa o comportamento de exibição do nome da categoria da etiqueta de dados de um gráfico especificado. |
| [getShowSeriesName()](#getShowSeriesName--) | Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série nas etiquetas de dados de um gráfico. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série nas etiquetas de dados de um gráfico. |
| [getShowPercentage()](#getShowPercentage--) | Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Representa o comportamento de exibição do valor do tamanho da bolha da etiqueta de dados de um gráfico especificado. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Representa o comportamento de exibição do valor do tamanho da bolha da etiqueta de dados de um gráfico especificado. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Representa o comportamento de exibição das linhas guias da etiqueta de dados de um gráfico especificado. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Representa o comportamento de exibição das linhas guias da etiqueta de dados de um gráfico especificado. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determina se a etiqueta de dados de um gráfico especificado será exibida como anotação de dados ou como etiqueta de dados. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determina se a etiqueta de dados de um gráfico especificado será exibida como anotação de dados ou como etiqueta de dados. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Representa o comportamento de exibição do valor da célula da etiqueta de dados de um gráfico especificado. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Representa o comportamento de exibição do valor da célula da etiqueta de dados de um gráfico especificado. |
| [getSeparator()](#getSeparator--) | Define ou retorna um Variant representando o separador usado nas etiquetas de dados de um gráfico. Leitura/gravação String. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Define ou retorna um Variant representando o separador usado nas etiquetas de dados de um gráfico. Leitura/gravação String. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados, então essa propriedade obtém ou define o valor padrão da propriedade IsNumberFormatLinkedToSource para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade IsNumberFormatLinkedToSource para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" faz com que todas as chamadas DataLabels.get_Item(i).isNumberFormatLinkedToSource() sejam iguais a val).

**Retorna:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados, então essa propriedade obtém ou define o valor padrão da propriedade IsNumberFormatLinkedToSource para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade IsNumberFormatLinkedToSource para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" faz com que todas as chamadas DataLabels.get_Item(i).isNumberFormatLinkedToSource() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Representa a string de formato para o objeto DataLabels. Leitura/gravação String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados, então essa propriedade obtém ou define o valor padrão da propriedade NumberFormat para as novas etiquetas de dados na coleção DataLabelCollection. Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" faz com que todas as chamadas DataLabels.get_Item(i).getNumberFormat() sejam iguais a val).

**Retorna:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Representa a string de formato para o objeto DataLabels. Leitura/gravação String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados, então essa propriedade obtém ou define o valor padrão da propriedade NumberFormat para as novas etiquetas de dados na coleção DataLabelCollection. Quando esta propriedade é definida com um valor, esse valor também é definido para a propriedade NumberFormat de todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" faz com que todas as chamadas DataLabels.get_Item(i).getNumberFormat() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Representa o formato da etiqueta de dados. Somente leitura [IFormat](../../com.aspose.slides/iformat).

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade representa o formato padrão para as novas etiquetas de dados na coleção DataLabelCollection.

**Retorna:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Representa a posição da etiqueta de dados. Leitura/gravação [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade Position para as novas etiquetas de dados na coleção DataLabelCollection. Representa a posição para os objetos DataLabel. Definir esta propriedade com um valor também define esse valor na propriedade Position para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setPosition(val)" faz com que todas as chamadas DataLabels.get_Item(i).getPosition() sejam iguais a val).

**Retorna:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Representa a posição da etiqueta de dados. Leitura/gravação [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade Position para as novas etiquetas de dados na coleção DataLabelCollection. Representa a posição para os objetos DataLabel. Definir esta propriedade com um valor também define esse valor na propriedade Position para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setPosition(val)" faz com que todas as chamadas DataLabels.get_Item(i).getPosition() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Representa o comportamento de exibição da chave de legenda da etiqueta de dados de um gráfico especificado. Verdadeiro se a chave de legenda da etiqueta de dados estiver visível. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLegendKey para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLegendKey para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLegendKey() sejam iguais a val).

**Retorna:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Representa o comportamento de exibição da chave de legenda da etiqueta de dados de um gráfico especificado. Verdadeiro se a chave de legenda da etiqueta de dados estiver visível. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLegendKey para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLegendKey para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLegendKey() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowValue para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowValue para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowValue() sejam iguais a val).

**Retorna:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowValue para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowValue para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowValue() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Representa o comportamento de exibição do nome da categoria da etiqueta de dados de um gráfico especificado. Verdadeiro para exibir o nome da categoria nas etiquetas de dados de um gráfico. Falso para ocultar. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowCategoryName para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowCategoryName para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowCategoryName() sejam iguais a val).

**Retorna:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Representa o comportamento de exibição do nome da categoria da etiqueta de dados de um gráfico especificado. Verdadeiro para exibir o nome da categoria nas etiquetas de dados de um gráfico. Falso para ocultar. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowCategoryName para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowCategoryName para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowCategoryName() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série nas etiquetas de dados de um gráfico. Verdadeiro para mostrar o nome da série. Falso para ocultar. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowSeriesName para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowSeriesName() sejam iguais a val).

**Retorna:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Retorna ou define um Boolean para indicar o comportamento de exibição do nome da série nas etiquetas de dados de um gráfico. Verdadeiro para mostrar o nome da série. Falso para ocultar. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowSeriesName para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowSeriesName para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowSeriesName() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowPercentage para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowPercentage para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowPercentage() sejam iguais a val).

**Retorna:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Representa o comportamento de exibição do valor percentual da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor percentual. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowPercentage para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowPercentage para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowPercentage() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Representa o comportamento de exibição do valor do tamanho da bolha da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor do tamanho da bolha. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowBubbleSize para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowBubbleSize para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowBubbleSize() sejam iguais a val).

**Retorna:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Representa o comportamento de exibição do valor do tamanho da bolha da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor do tamanho da bolha. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowBubbleSize para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowBubbleSize para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowBubbleSize() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Representa o comportamento de exibição das linhas guias da etiqueta de dados de um gráfico especificado. Verdadeiro exibe as linhas guias. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLeaderLines para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLeaderLines para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLeaderLines() sejam iguais a val).

**Retorna:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Representa o comportamento de exibição das linhas guias da etiqueta de dados de um gráfico especificado. Verdadeiro exibe as linhas guias. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLeaderLines para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLeaderLines para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLeaderLines() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Determina se a etiqueta de dados de um gráfico especificado será exibida como anotação de dados ou como etiqueta de dados.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelAsDataCallout para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLabelAsDataCallout para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLabelAsDataCallout() sejam iguais a val).

**Retorna:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Determina se a etiqueta de dados de um gráfico especificado será exibida como anotação de dados ou como etiqueta de dados.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelAsDataCallout para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLabelAsDataCallout para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLabelAsDataCallout() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Representa o comportamento de exibição do valor da célula da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor da célula. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelValueFromCell para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLabelValueFromCell para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLabelValueFromCell() sejam iguais a val).

**Retorna:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Representa o comportamento de exibição do valor da célula da etiqueta de dados de um gráfico especificado. Verdadeiro exibe o valor da célula. Falso oculta. Leitura/gravação boolean.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade ShowLabelValueFromCell para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade ShowLabelValueFromCell para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" faz com que todas as chamadas DataLabels.get_Item(i).getShowLabelValueFromCell() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Define ou retorna um Variant representando o separador usado nas etiquetas de dados de um gráfico. Leitura/gravação String.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade Separator para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade Separator para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" faz com que todas as chamadas DataLabels.get_Item(i).getSeparator() sejam iguais a val).

**Retorna:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Define ou retorna um Variant representando o separador usado nas etiquetas de dados de um gráfico. Leitura/gravação String.

--------------------

Se o pai deste objeto DataLabelFormat for uma coleção DataLabelCollection de etiquetas de dados então esta propriedade obtém ou define o valor padrão da propriedade Separator para as novas etiquetas de dados na coleção DataLabelCollection. Definir esta propriedade com um valor também define esse valor na propriedade Separator para todas as etiquetas de dados na coleção DataLabelCollection (por exemplo, "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" faz com que todas as chamadas DataLabels.get_Item(i).getSeparator() sejam iguais a val).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |