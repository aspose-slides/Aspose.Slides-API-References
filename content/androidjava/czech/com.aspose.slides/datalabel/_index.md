---
title: DataLabel
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje popisky řady.
type: docs
url: /cs/com.aspose.slides/datalabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Reprezentuje popisky řady.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Vytvoří novou instanci třídy DataLabel. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [isVisible()](#isVisible--) | False znamená, že datový popisek není viditelný (a proto jsou všechny Show*-flags (ShowValue, ...) nastaveny na false). |
| [hide()](#hide--) | Skryjte datový popisek nastavením všech Show*-flags (ShowValue, ...) do stavu false. |
| [getActualLabelText()](#getActualLabelText--) | Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializuje TextFrameForOverriding textem z parametru "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Může obsahovat bohatě formátovaný text. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu. |
| [getX()](#getX--) | Vrací nebo nastavuje souřadnici x nadpisu jako zlomek šířky grafu. |
| [setX(float value)](#setX-float-) | Vrací nebo nastavuje souřadnici x nadpisu jako zlomek šířky grafu. |
| [getY()](#getY--) | Vrací nebo nastavuje souřadnici y nadpisu jako zlomek výšky grafu. |
| [setY(float value)](#setY-float-) | Vrací nebo nastavuje souřadnici y nadpisu jako zlomek výšky grafu. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku nadpisu jako zlomek šířky grafu. |
| [setWidth(float value)](#setWidth-float-) | Vrací nebo nastavuje šířku nadpisu jako zlomek šířky grafu. |
| [getHeight()](#getHeight--) | Vrací nebo nastavuje výšku nadpisu jako zlomek výšky grafu. |
| [setHeight(float value)](#setHeight-float-) | Vrací nebo nastavuje výšku nadpisu jako zlomek výšky grafu. |
| [getRight()](#getRight--) | Vpravo. |
| [getBottom()](#getBottom--) | Dole. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Vrací formát datového popisku. |
| [getValueFromCell()](#getValueFromCell--) | Získá nebo nastaví buňku datového sešitu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Získá nebo nastaví buňku datového sešitu. |
| [getActualX()](#getActualX--) | Určuje skutečnou polohu x (levá) elementu grafu vzhledem k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečnou horní polohu elementu grafu vzhledem k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku elementu grafu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku elementu grafu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci FillFormat. |
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

False znamená, že datový popisek není viditelný (a proto jsou všechny Show*-flags (ShowValue, ...) nastaveny na false). Pouze pro čtení boolean.

Pokud je datový popisek viditelný, můžete jej skrýt pomocí metody Hide(). Pokud však datový popisek není viditelný (IsVisible je false), můžete jej zobrazit nastavením Show*-flags (ShowValue, ...) do stavu true.

**Vrací:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Skryje datový popisek nastavením všech Show*-flags (ShowValue, ...) do stavu false. Po tomto bude IsVisible false.

**Vrací:**
boolean
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

Inicializuje TextFrameForOverriding textem z parametru "text". Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text.

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

Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, pak tato hodnota formátovaného textu přepíše automaticky generovaný text datového popisku. Automaticky generovaný text datového popisku znamená text, který spravují vlastnosti ShowSeriesName, ShowValue, ... a je formátován pomocí vlastnosti TextFormatManager.TextFormat. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

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

Vrací nebo nastavuje souřadnici x nadpisu jako zlomek šířky grafu. Čtení/Zápis float.

**Vrací:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Vrací nebo nastavuje souřadnici x nadpisu jako zlomek šířky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```

Vrací nebo nastavuje souřadnici y nadpisu jako zlomek výšky grafu. Čtení/Zápis float.

**Vrací:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Vrací nebo nastavuje souřadnici y nadpisu jako zlomek výšky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```

Vrací nebo nastavuje šířku nadpisu jako zlomek šířky grafu. Čtení/Zápis float.

**Vrací:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Vrací nebo nastavuje šířku nadpisu jako zlomek šířky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```

Vrací nebo nastavuje výšku nadpisu jako zlomek výšky grafu. Čtení/Zápis float.

**Vrací:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Vrací nebo nastavuje výšku nadpisu jako zlomek výšky grafu. Čtení/Zápis float.

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

Vrací formát datového popisku. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Získá nebo nastaví buňku datového sešitu. Použito, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Získá nebo nastaví buňku datového sešitu. Použito, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualX() {#getActualX--}
```
public final float getActualX()
```

Určuje skutečnou polohu x (levá) elementu grafu vzhledem k levému hornímu rohu grafu. Před voláním této metody je nutné zavolat IChart.ValidateChartLayout() pro získání skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Určuje skutečnou horní polohu elementu grafu vzhledem k levému hornímu rohu grafu. Před voláním této metody je nutné zavolat IChart.ValidateChartLayout() pro získání skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Určuje skutečnou šířku elementu grafu. Před voláním této metody je nutné zavolat IChart.ValidateChartLayout() pro získání skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Určuje skutečnou výšku elementu grafu. Před voláním této metody je nutné zavolat IChart.ValidateChartLayout() pro získání skutečných hodnot. Pouze pro čtení float.

**Vrací:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)