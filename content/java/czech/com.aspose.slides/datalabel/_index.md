---
title: DataLabel
second_title: Aspose.Slides pro Java – reference API
description: Představuje popisky řady.
type: docs
url: /cs/com.aspose.slides/datalabel/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Představuje popisky řady.
## Konstruktor

| Konstruktor | Popis |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Vytvoří novou instanci třídy DataLabel. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [isVisible()](#isVisible--) | False znamená, že popisek dat není viditelný (a všechny Show*-flags (ShowValue, …) jsou false). |
| [hide()](#hide--) | Skryje popisek dat nastavením všech Show*-flags (ShowValue, …) na false. |
| [getActualLabelText()](#getActualLabelText--) | Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializuje TextFrameForOverriding textem v parametru „text“. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Může obsahovat bohatě formátovaný text. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu. |
| [getX()](#getX--) | Vrací nebo nastavuje souřadnici x titulku jako zlomek šířky grafu. |
| [setX(float value)](#setX-float-) | Vrací nebo nastavuje souřadnici x titulku jako zlomek šířky grafu. |
| [getY()](#getY--) | Vrací nebo nastavuje souřadnici y titulku jako zlomek výšky grafu. |
| [setY(float value)](#setY-float-) | Vrací nebo nastavuje souřadnici y titulku jako zlomek výšky grafu. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku titulku jako zlomek šířky grafu. |
| [setWidth(float value)](#setWidth-float-) | Vrací nebo nastavuje šířku titulku jako zlomek šířky grafu. |
| [getHeight()](#getHeight--) | Vrací nebo nastavuje výšku titulku jako zlomek výšky grafu. |
| [setHeight(float value)](#setHeight-float-) | Vrací nebo nastavuje výšku titulku jako zlomek výšky grafu. |
| [getRight()](#getRight--) | Vpravo. |
| [getBottom()](#getBottom--) | Dole. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Vrací formát popisku dat. |
| [getValueFromCell()](#getValueFromCell--) | Získá nebo nastaví buňku dat sešitu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Získá nebo nastaví buňku dat sešitu. |
| [getLabelShapeType()](#getLabelShapeType--) | Získá nebo nastaví typ tvaru popisku dat. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Získá nebo nastaví typ tvaru popisku dat. |
| [getActualX()](#getActualX--) | Určuje skutečnou polohu x (vlevo) prvku grafu relativně k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečnou horní polohu prvku grafu relativně k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku prvku grafu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku prvku grafu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Vytvoří novou instanci třídy DataLabel.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Nadřazený ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False znamená, že popisek dat není viditelný (a všechny Show*-flags (ShowValue, …) jsou false). Pouze pro čtení boolean.

--------------------

Pokud je popisek dat viditelný, můžete jej skrýt metodou Hide(). Pokud popisek dat není viditelný (IsVisible je false), můžete jej zobrazit nastavením Show*-flags (ShowValue, …) na true.

**Vrací:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Skryje popisek dat nastavením všech Show*-flags (ShowValue, …) na false. IsVisible bude po tomto false.

--------------------

Pokud popisek dat není viditelný (IsVisible je false), můžete jej zobrazit nastavením Show*-flags (ShowValue, …) na true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text.

**Vrací:**
java.lang.String - Objekt java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializuje TextFrameForOverriding textem v parametru „text“. Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text pro nový TextFrameForOverriding. |

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, pak tato formátovaná textová hodnota přepíše automaticky generovaný text popisku dat. Automaticky generovaný text popisku dat znamená text řízený pomocí vlastností ShowSeriesName, ShowValue, … a formátovaný vlastností TextFormatManager.TextFormat. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Vrací formát textu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Vrací nebo nastavuje souřadnici x titulku jako zlomek šířky grafu. Čtení/Zápis float.

**Vrací:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Vrací nebo nastavuje souřadnici x titulku jako zlomek šířky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Vrací nebo nastavuje souřadnici y titulku jako zlomek výšky grafu. Čtení/Zápis float.

**Vrací:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Vrací nebo nastavuje souřadnici y titulku jako zlomek výšky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Vrací nebo nastavuje šířku titulku jako zlomek šířky grafu. Čtení/Zápis float.

**Vrací:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Vrací nebo nastavuje šířku titulku jako zlomek šířky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Vrací nebo nastavuje výšku titulku jako zlomek výšky grafu. Čtení/Zápis float.

**Vrací:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Vrací nebo nastavuje výšku titulku jako zlomek výšky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```

Vpravo. Pouze pro čtení float.

**Vrací:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Dole. Pouze pro čtení float.

**Vrací:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Vrací formát popisku dat. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Získá nebo nastaví buňku dat sešitu. Používá se, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Získá nebo nastaví buňku dat sešitu. Používá se, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```

Získá nebo nastaví typ tvaru popisku dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) pokud není definován žádný tvar.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru prvního popisku dat na Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```

Získá nebo nastaví typ tvaru popisku dat. Vrací [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) pokud není definován žádný tvar.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Nastavte typ tvaru prvního popisku dat na Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Určuje skutečnou pozici x (vlevo) prvku grafu relativně k levému hornímu rohu grafu. Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot. Čtení float.

**Vrací:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Určuje skutečnou horní pozici prvku grafu relativně k levému hornímu rohu grafu. Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot. Čtení float.

**Vrací:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Určuje skutečnou šířku prvku grafu. Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot. Čtení float.

**Vrací:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Určuje skutečnou výšku prvku grafu. Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot. Čtení float.

**Vrací:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)