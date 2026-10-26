---
title: DataLabelCollection
second_title: Aspose.Slides Android számára a Java API referenciája
description: Egy sor címkéit képviseli.
type: docs
url: /hu/com.aspose.slides/datalabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Egy sor címkéit képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végig iterálja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show\*-flags (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímkét alapértelmezés szerint elrejti, ha a DefaultDataLabelFormat tulajdonság összes Show\*-flags (ShowValue, ...) hamis állapotra állítja. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lekéri a gyűjteményben lévő látható adatcímkék számát. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő összes adatcímke számát. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Lekéri az alapértelmezett adatcímke formátumot. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Képviseli az adatcímkék vezetővonal formátumát. |
| [getParentSeries()](#getParentSeries--) | Lekéri a szülő sorozatot. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű adatponthoz tartozó adatcímkét. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diaját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációját. |
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


Visszaad egy enumerátort, amely végig iterálja a gyűjteményt.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```


Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show\*-flags (ShowValue, ...) hamis). Csak olvasható boolean.

--------------------

Ha az adatcímke alapértelmezés szerint látható, akkor a Hide() metódussal tehetjük alapértelmezés szerint rejtetté. Ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), akkor a DefaultDataLabelFormat tulajdonság Show\*-flags (ShowValue, ...) true állapotra állításával tehetjük az adatcímkét „alapértelmezés szerint láthatóvá”.

**Visszatér:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Az adatcímkét alapértelmezés szerint elrejti, ha a DefaultDataLabelFormat tulajdonság összes Show\*-flags (ShowValue, ...) hamis állapotra állítja. Ez után az IsVisible hamis lesz.

--------------------

Ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), akkor a DefaultDataLabelFormat tulajdonság Show\*-flags (ShowValue, ...) true állapotra állításával tehetjük az adatcímkét „alapértelmezés szerint láthatóvá”.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```


Lekéri a gyűjteményben lévő látható adatcímkék számát. Csak olvasható int.

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


Képviseli az adatcímkék vezetővonal formátumát. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
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
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Megkeresendő DataLabel. |

**Visszatér:**
int - A DataLabel indexe, vagy -1, ha a DataLabel nem ebben a gyűjteményben van.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```


Lekéri a megadott indexű adatponthoz tartozó adatcímkét.

--------------------

Az adatcímke elérésének alternatív módja: - series.getDataPoints().get_Item(i).getLabel() - címke tulajdonságok kezelése.

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


Visszaadja a FillFormat szülő diaját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)