---
title: DataLabelCollection
second_title: Aspose.Slides Java API referencia
description: A sorozat címkéit képviseli.
type: docs
url: /hu/com.aspose.slides/datalabelcollection/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

A sorozat címkéit képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). |
| [hide()](#hide--) | Tegye alapértelmezés szerint rejtetté az adatcímkét, az összes Show*-jelző (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban hamis állapotba állítva. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lekéri a gyűjteményben látható adatcímkék számát. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő összes adatcímke számát. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Lekéri az alapértelmezett adatcímke formátumot. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Az adatcímkék vezetővonal formátumát ábrázolja. |
| [getParentSeries()](#getParentSeries--) | Lekéri a szülő sorozatot. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű adatpont adatcímkéjét. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő bemutatóját. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Visszaad egy enumerátort, amely végigjárja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator, amely a gyűjtemény bejárására használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Egy java.util.Iterator a teljes gyűjteményhez.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). Csak olvasható boolean.

--------------------

Ha az adatcímke alapértelmezés szerint látható, a Hide() metódussal tehető alapértelmezés szerint rejtetté. De ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), a DefaultDataLabelFormat tulajdonság Show*-jelzőinek (ShowValue, ...) true állapotra állításával tehető alapértelmezés szerint láthatóvá.

**Visszatér:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Tegye alapértelmezés szerint rejtetté az adatcímkét, az összes Show*-jelzőt (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban hamis állapotra állítva. Ez után az IsVisible hamis lesz.

--------------------

Ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), a DefaultDataLabelFormat tulajdonság Show*-jelzőinek (ShowValue, ...) true állapotra állításával tehető alapértelmezés szerint láthatóvá.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Lekéri a gyűjteményben látható adatcímkék számát. Csak olvasható int.

**Visszatér:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

Lekéri a gyűjteményben lévő összes adatcímke számát. Csak olvasható int.

**Visszatér:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Lekéri az alapértelmezett adatcímke formátumot. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatér:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Az adatcímkék vezetővonal formátumát ábrázolja. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Lekéri a szülő sorozatot. Csak olvasható [IChartSeries](../../com.aspose.slides/ichartseries).

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Visszaadja a megadott DataLabel indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | A keresendő DataLabel. |

**Visszatér:**
int - A DataLabel indexe vagy -1, ha a DataLabel nem ebből a gyűjteményből származik.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Lekéri a megadott indexű adatpont adatcímkéjét.

--------------------

Az adatcímke elérésének alternatív módja: - series.getDataPoints().get_Item(i).getLabel() - a címke tulajdonságainak kezelése.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő bemutatóját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)