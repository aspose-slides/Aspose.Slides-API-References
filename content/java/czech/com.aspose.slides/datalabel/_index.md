---
title: DataLabel
second_title: Aspose.Slides pro Java - reference API
description: Reprezentuje popisky řady.
type: docs
url: /cs/com.aspose.slides/datalabel/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
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
| [isVisible()](#isVisible--) | False znamená, že datový popisek není viditelný (a tak všechny příznaky Show*-flags (ShowValue, ...) jsou false). |
| [hide()](#hide--) | Skryjte datový popisek nastavením všech příznaků Show*-flags (ShowValue, ...) do stavu false. |
| [getActualLabelText()](#getActualLabelText--) | Vrací aktuální text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializuje TextFrameForOverriding textem v parametru "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Může obsahovat bohatě formátovaný text. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu. |
| [getX()](#getX--) | Vrací nebo nastavuje souřadnici x popisku jako zlomek šířky grafu. |
| [setX(float value)](#setX-float-) | Vrací nebo nastavuje souřadnici x popisku jako zlomek šířky grafu. |
| [getY()](#getY--) | Vrací nebo nastavuje souřadnici y popisku jako zlomek výšky grafu. |
| [setY(float value)](#setY-float-) | Vrací nebo nastavuje souřadnici y popisku jako zlomek výšky grafu. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku popisku jako zlomek šířky grafu. |
| [setWidth(float value)](#setWidth-float-) | Vrací nebo nastavuje šířku popisku jako zlomek šířky grafu. |
| [getHeight()](#getHeight--) | Vrací nebo nastavuje výšku popisku jako zlomek výšky grafu. |
| [setHeight(float value)](#setHeight-float-) | Vrací nebo nastavuje výšku popisku jako zlomek výšky grafu. |
| [getRight()](#getRight--) | Vpravo. |
| [getBottom()](#getBottom--) | Dole. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Vrací formát datového popisku. |
| [getValueFromCell()](#getValueFromCell--) | Získá nebo nastaví buňku dat sešitu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Získá nebo nastaví buňku dat sešitu. |
| [getActualX()](#getActualX--) | Udává skutečnou pozici x (levá) prvku grafu relativně k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Udává skutečnou horní pozici prvku grafu relativně k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Udává skutečnou šířku prvku grafu. |
| [getActualHeight()](#getActualHeight--) | Udává skutečnou výšku prvku grafu. |
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

**Návratová hodnota:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False znamená, že datový popisek není viditelný (a tak všechny příznaky Show*-flags (ShowValue, ...) jsou false). Pouze pro čtení boolean.

--------------------

Pokud je datový popisek viditelný, můžete jej skrýt metodou Hide(). Pokud není (IsVisible je false), můžete jej zobrazit nastavením příznaků Show*-flags (ShowValue, ...) do stavu true.

**Návratová hodnota:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Skryje datový popisek nastavením všech příznaků Show*-flags (ShowValue, ...) do stavu false. Po volání bude IsVisible false.

--------------------

Pokud není datový popisek viditelný (IsVisible je false), můžete jej zobrazit nastavením příznaků Show*-flags (ShowValue, ...) do stavu true.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Vrací aktuální text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text.

**Návratová hodnota:**
java.lang.String - Objekt java.lang.String.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializuje TextFrameForOverriding textem v parametru "text". Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text pro nový TextFrameForOverriding. |

**Návratová hodnota:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Může obsahovat bohatě formátovaný text. Pokud není tato vlastnost null, pak tento formátovaný text přepíše automaticky generovaný text datového popisku. Automaticky generovaný text datového popisku je text řízený vlastnostmi ShowSeriesName, ShowValue, ... a formátovaný pomocí TextFormatManager.TextFormat. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Návratová hodnota:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Vrací formát textu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Návratová hodnota:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Vrací nebo nastavuje souřadnici x popisku jako zlomek šířky grafu. Čtení/Zápis float.

**Návratová hodnota:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Vrací nebo nastavuje souřadnici x popisku jako zlomek šířky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Vrací nebo nastavuje souřadnici y popisku jako zlomek výšky grafu. Čtení/Zápis float.

**Návratová hodnota:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Vrací nebo nastavuje souřadnici y popisku jako zlomek výšky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Vrací nebo nastavuje šířku popisku jako zlomek šířky grafu. Čtení/Zápis float.

**Návratová hodnota:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Vrací nebo nastavuje šířku popisku jako zlomek šířky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Vrací nebo nastavuje výšku popisku jako zlomek výšky grafu. Čtení/Zápis float.

**Návratová hodnota:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Vrací nebo nastavuje výšku popisku jako zlomek výšky grafu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Vpravo. Pouze pro čtení float.

**Návratová hodnota:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Dole. Pouze pro čtení float.

**Návratová hodnota:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Vrací formát datového popisku. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Návratová hodnota:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Získá nebo nastaví buňku dat sešitu. Používá se, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Návratová hodnota:**
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

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Udává skutečnou pozici x (levá) prvku grafu relativně k levému hornímu rohu grafu. Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze čtení float.

**Návratová hodnota:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Udává skutečnou horní pozici prvku grafu relativně k levému hornímu rohu grafu. Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze čtení float.

**Návratová hodnota:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Udává skutečnou šířku prvku grafu. Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze čtení float.

**Návratová hodnota:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Udává skutečnou výšku prvku grafu. Před získáním skutečných hodnot zavolejte metodu IChart.ValidateChartLayout(). Pouze čtení float.

**Návratová hodnota:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Návratová hodnota:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Návratová hodnota:**
[IPresentation](../../com.aspose.slides/ipresentation)