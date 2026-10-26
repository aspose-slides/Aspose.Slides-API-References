---
title: IDataLabel
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa rótulos de série.
type: docs
url: /pt/com.aspose.slides/idatalabel/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Representa rótulos de série.
## Métodos

| Método | Descrição |
| --- | --- |
| [isVisible()](#isVisible--) | False significa que o rótulo de dados não está visível (e assim todas as flags Show*- (ShowValue, ...) são false). |
| [hide()](#hide--) | Torna o rótulo de dados oculto definindo todas as flags Show*- (ShowValue, ...) para o estado false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Retorna o formato do rótulo de dados. |
| [getValueFromCell()](#getValueFromCell--) | Obtém ou define a célula de dados da planilha. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Obtém ou define a célula de dados da planilha. |
| [getActualLabelText()](#getActualLabelText--) | Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False significa que o rótulo de dados não está visível (e assim todas as flags Show*- (ShowValue, ...) são false). Somente leitura boolean.

--------------------

Se o rótulo de dados estiver visível, você pode ocultá-lo com o método Hide(). Mas se o rótulo de dados não estiver visível (IsVisible é false) você pode tornar o rótulo de dados visível definindo as flags Show*- (ShowValue, ...) para o estado true.

**Retorna:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Torna o rótulo de dados oculto definindo todas as flags Show*- (ShowValue, ...) para o estado false. IsVisible será false após isso.

--------------------

Se o rótulo de dados não estiver visível (IsVisible é false) você pode tornar o rótulo de dados visível definindo as flags Show*- (ShowValue, ...) para o estado true.

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

Obtém ou define a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

**Retorna:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Obtém ou define a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for true.

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
java.lang.String - Texto real do rótulo