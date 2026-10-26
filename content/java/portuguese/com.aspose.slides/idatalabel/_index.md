---
title: IDataLabel
second_title: Aspose.Slides para Referência da API Java
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/idatalabel/
---
**Todas as interfaces implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Representa rótulos de série.
## Métodos

| Método | Descrição |
| --- | --- |
| [isVisible()](#isVisible--) | False significa que o rótulo de dados não está visível (e, portanto, todas as flags Show*- (ShowValue, ...) são falsas). |
| [hide()](#hide--) | Oculta o rótulo de dados definindo todas as flags Show*- (ShowValue, ...) para o estado falso. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retorna o formato do rótulo de dados. |
| [getValueFromCell()](#getValueFromCell--) | Obtém ou define a célula de dados da pasta de trabalho. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtém ou define a célula de dados da pasta de trabalho. |
| [getActualLabelText()](#getActualLabelText--) | Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False significa que o rótulo de dados não está visível (e, portanto, todas as flags Show*- (ShowValue, ...) são falsas). Boolean de somente leitura.

--------------------

Se o rótulo de dados estiver visível, você pode ocultá-lo com o método Hide(). Mas se o rótulo de dados não estiver visível (IsVisible é false), você pode torná-lo visível definindo as flags Show*- (ShowValue, ...) para o estado verdadeiro.

**Retorna:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Oculta o rótulo de dados definindo todas as flags Show*- (ShowValue, ...) para o estado falso. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível (IsVisible é false), você pode torná-lo visível definindo as flags Show*- (ShowValue, ...) para o estado verdadeiro.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Retorna o formato do rótulo de dados. Somente leitura [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Retorna:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtém ou define a célula de dados da pasta de trabalho. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text.

**Retorna:**
java.lang.String - String de texto real do rótulo