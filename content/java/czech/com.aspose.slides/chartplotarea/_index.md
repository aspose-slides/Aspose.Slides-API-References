---
title: ChartPlotArea
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje obdélník, kde má být vykreslen graf.
type: docs
url: /cs/com.aspose.slides/chartplotarea/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartPlotArea](../../com.aspose.slides/ichartplotarea)
```
public class ChartPlotArea extends DomObject<Chart> implements IChartPlotArea
```

Representuje obdélník, kde by měl být vykreslen graf.
## Metody

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) | Vrací formát ploše vykreslování. |
| [getX()](#getX--) | Vrací nebo nastavuje souřadnici X levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). |
| [setX(float value)](#setX-float-) | Vrací nebo nastavuje souřadnici X levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). |
| [getY()](#getY--) | Vrací nebo nastavuje souřadnici Y levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). |
| [setY(float value)](#setY-float-) | Vrací nebo nastavuje souřadnici Y levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). |
| [setWidth(float value)](#setWidth-float-) | Vrací nebo nastavuje šířku rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). |
| [getHeight()](#getHeight--) | Vrací nebo nastavuje výšku rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). |
| [setHeight(float value)](#setHeight-float-) | Vrací nebo nastavuje výšku rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). |
| [getRight()](#getRight--) | Vpravo. |
| [getBottom()](#getBottom--) | Dole. |
| [getChart()](#getChart--) | Graf. |
| [isLocationAutocalculated()](#isLocationAutocalculated--) | Definuje, jak má být poloha vypočítána: true – vypočítáno automaticky; definováno vlastnostmi X, Y, Width, Height. |
| [getLayoutTargetType()](#getLayoutTargetType--) | Pokud je rozvržení ploše vykreslování definováno ručně, tato vlastnost určuje, zda rozvržení ploše vykreslování provádět dle jejího vnitřku (bez os a popisků os) nebo vně (s osami a popisky os). |
| [setLayoutTargetType(int value)](#setLayoutTargetType-int-) | Pokud je rozvržení ploše vykreslování definováno ručně, tato vlastnost určuje, zda rozvržení ploše vykreslování provádět dle jejího vnitřku (bez os a popisků os) nebo vně (s osami a popisky os). |
| [getActualX()](#getActualX--) | Určuje skutečnou souřadnici X (levá) prvku grafu relativně k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečný horní okraj prvku grafu relativně k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku prvku grafu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku prvku grafu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Vrací formát ploše vykreslování. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### getX() {#getX--}
```
public final float getX()
```

Vrací nebo nastavuje souřadnici X levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). Čtení/zápis float.

**Vrací:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Vrací nebo nastavuje souřadnici X levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Vrací nebo nastavuje souřadnici Y levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). Čtení/zápis float.

**Vrací:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Vrací nebo nastavuje souřadnici Y levého horního rohu ohraničujícího rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Vrací nebo nastavuje šířku rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). Čtení/zápis float.

**Vrací:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Vrací nebo nastavuje šířku rámečku ploše vykreslování jako zlomek šířky grafu (od 0 do 1). Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Vrací nebo nastavuje výšku rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). Čtení/zápis float.

**Vrací:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Vrací nebo nastavuje výšku rámečku ploše vykreslování jako zlomek výšky grafu (od 0 do 1). Čtení/zápis float.

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

### getChart() {#getChart--}
```
public final IChart getChart()
```

Graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)

### isLocationAutocalculated() {#isLocationAutocalculated--}
```
public final boolean isLocationAutocalculated()
```

Definuje, jak má být poloha vypočítána: true – vypočítáno automaticky; definováno vlastnostmi X, Y, Width, Height. Pouze pro čtení boolean.

**Vrací:**
boolean

### getLayoutTargetType() {#getLayoutTargetType--}
```
public final int getLayoutTargetType()
```

Pokud je rozvržení ploše vykreslování definováno ručně, tato vlastnost určuje, zda rozvržení ploše vykreslování provádět dle jejího vnitřku (bez os a popisků os) nebo vně (s osami a popisky os). Čtení/zápis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```


**Vrací:**
int

### setLayoutTargetType(int value) {#setLayoutTargetType-int-}
```
public final void setLayoutTargetType(int value)
```

Pokud je rozvržení ploše vykreslování definováno ručně, tato vlastnost určuje, zda rozvržení ploše vykreslování provádět dle jejího vnitřku (bez os a popisků os) nebo vně (s osami a popisky os). Čtení/zápis [LayoutTargetType](../../com.aspose.slides/layouttargettype)(\#getLayoutTargetType.getLayoutTargetType/\#setLayoutTargetType(int).setLayoutTargetType(int)).

--------------------

> ```
> Presentation presentation = new Presentation();
>   try
>   {
>       ISlide slide = presentation.getSlides().get_Item(0);
>       IChart chart = slide.getShapes().addChart(ChartType.ClusteredColumn, 20, 100, 600, 400);
>       chart.getPlotArea().setX(0.2f);
>       chart.getPlotArea().setY(0.2f);
>       chart.getPlotArea().setWidth(0.7f);
>       chart.getPlotArea().setHeight(0.7f);
>       chart.getPlotArea().setLayoutTargetType(LayoutTargetType.Inner);
>       ...
>   } finally {
>       if (presentation != null) presentation.dispose();
>   }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Určuje skutečnou souřadnici X (levá) prvku grafu relativně k levému hornímu rohu grafu. Před tím zavolejte metodu IChart.ValidateChartLayout(), aby se získaly skutečné hodnoty. Čtení float.

**Vrací:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Určuje skutečný horní okraj prvku grafu relativně k levému hornímu rohu grafu. Před tím zavolejte metodu IChart.ValidateChartLayout(), aby se získaly skutečné hodnoty. Čtení float.

**Vrací:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Určuje skutečnou šířku prvku grafu. Před tím zavolejte metodu IChart.ValidateChartLayout(), aby se získaly skutečné hodnoty. Čtení float.

**Vrací:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Určuje skutečnou výšku prvku grafu. Před tím zavolejte metodu IChart.ValidateChartLayout(), aby se získaly skutečné hodnoty. Čtení float.

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