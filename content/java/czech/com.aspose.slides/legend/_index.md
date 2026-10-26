---
title: Legend
second_title: Aspose.Slides pro Java API Reference
description: Představuje vlastnosti legendy grafu.
type: docs
url: /cs/com.aspose.slides/legend/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ILegend](../../com.aspose.slides/ilegend)
```
public class Legend extends DomObject<Chart> implements ILegend
```

Představuje vlastnosti legendy grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getX()](#getX--) | Vrací nebo nastavuje x-souřadnici legendy jako zlomek šířky grafu. |
| [setX(float value)](#setX-float-) | Vrací nebo nastavuje x-souřadnici legendy jako zlomek šířky grafu. |
| [getY()](#getY--) | Vrací nebo nastavuje y-souřadnici legendy jako zlomek výšky grafu. |
| [setY(float value)](#setY-float-) | Vrací nebo nastavuje y-souřadnici legendy jako zlomek výšky grafu. |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku legendy jako zlomek šířky grafu. |
| [setWidth(float value)](#setWidth-float-) | Vrací nebo nastavuje šířku legendy jako zlomek šířky grafu. |
| [getHeight()](#getHeight--) | Vrací nebo nastavuje výšku legendy jako zlomek výšky grafu. |
| [setHeight(float value)](#setHeight-float-) | Vrací nebo nastavuje výšku legendy jako zlomek výšky grafu. |
| [getRight()](#getRight--) | Vpravo. |
| [getBottom()](#getBottom--) | Dole. |
| [getOverlay()](#getOverlay--) | Určuje, zda mohou být ostatní prvky grafu překryty legendou. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Určuje, zda mohou být ostatní prvky grafu překryty legendou. |
| [getTextFormat()](#getTextFormat--) | Formát textu. |
| [getPosition()](#getPosition--) | Určuje polohu legendy v grafu. |
| [setPosition(int value)](#setPosition-int-) | Určuje polohu legendy v grafu. |
| [getFormat()](#getFormat--) | Vrací formát legendy. |
| [getChart()](#getChart--) | Vrací graf. |
| [getEntries()](#getEntries--) | Získává položky legendy. |
| [getActualX()](#getActualX--) | Určuje skutečnou x-pozici (levý okraj) prvku grafu vzhledem k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečnou horní pozici prvku grafu vzhledem k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku prvku grafu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku prvku grafu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |
### getX() {#getX--}
```
public final float getX()
```


Vrací nebo nastavuje x-souřadnici legendy jako zlomek šířky grafu. Čtení/zápis float.

**Vrací:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Vrací nebo nastavuje x-souřadnici legendy jako zlomek šířky grafu. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


Vrací nebo nastavuje y-souřadnici legendy jako zlomek výšky grafu. Čtení/zápis float.

**Vrací:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Vrací nebo nastavuje y-souřadnici legendy jako zlomek výšky grafu. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


Vrací nebo nastavuje šířku legendy jako zlomek šířky grafu. Čtení/zápis float.

**Vrací:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Vrací nebo nastavuje šířku legendy jako zlomek šířky grafu. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


Vrací nebo nastavuje výšku legendy jako zlomek výšky grafu. Čtení/zápis float.

**Vrací:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Vrací nebo nastavuje výšku legendy jako zlomek výšky grafu. Čtení/zápis float.

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
### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```


Určuje, zda mohou být ostatní prvky grafu překryty legendou. Čtení/zápis boolean.

**Vrací:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```


Určuje, zda mohou být ostatní prvky grafu překryty legendou. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Formát textu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Určuje polohu legendy v grafu. Hodnoty X, Y, Width, Height, které nejsou NaN, přepisují efekt této vlastnosti. Čtení/zápis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Určuje polohu legendy v grafu. Hodnoty X, Y, Width, Height, které nejsou NaN, přepisují efekt této vlastnosti. Čtení/zápis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Vrací formát legendy. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Vrací graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)
### getEntries() {#getEntries--}
```
public final ILegendEntryCollection getEntries()
```


Získává položky legendy. Pouze pro čtení [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Vrací:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Určuje skutečnou x-pozici (levý okraj) prvku grafu vzhledem k levému hornímu rohu grafu. Před voláním metody IChart.validateChartLayout() získáte skutečné hodnoty. Čtení float.

**Vrací:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Určuje skutečnou horní pozici prvku grafu vzhledem k levému hornímu rohu grafu. Před voláním metody IChart.validateChartLayout() získáte skutečné hodnoty. Čtení float.

**Vrací:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Určuje skutečnou šířku prvku grafu. Před voláním metody IChart.validateChartLayout() získáte skutečné hodnoty. Čtení float.

**Vrací:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Určuje skutečnou výšku prvku grafu. Před voláním metody IChart.validateChartLayout() získáte skutečné hodnoty. Čtení float.

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