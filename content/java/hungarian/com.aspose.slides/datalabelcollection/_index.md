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
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |
| [isVisible()](#isVisible--) | A false azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság minden Show*-flagja (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímkét alapértelmezés szerint rejtetté teszi a DefaultDataLabelFormat tulajdonság minden Show*-flagjának (ShowValue, ...) hamis állapotra állításával. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lekéri a látható adatcímkék számát a gyűjteményben. |
| [getCount()](#getCount--) | Lekéri az összes adatcímke számát a gyűjteményben. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Lekéri az alapértelmezett adatcímke formátumot. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Adatcímkék vezetővonal formátumát képviseli. |
| [getParentSeries()](#getParentSeries--) | Lekéri a szülő sorozatot. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű adatpont adatcímkéjét. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Lekéri vagy beállítja az adatcímkék alapértelmezett alakzat típusát. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Lekéri vagy beállítja az adatcímkék alapértelmezett alakzat típusát. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diát. |
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

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

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

A false azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság minden Show*-flagja (ShowValue, ...) hamis). Csak olvasható boolean.

--------------------

Ha az adatcímke alapértelmezés szerint látható, akkor a Hide() metódussal alapértelmezés szerint rejtetté tehető. De ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), akkor a DefaultDataLabelFormat tulajdonság Show*-flagjaival (ShowValue, ...) true állapotra állításával tehető "alapértelmezés szerint láthatóvá".

**Visszatér:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Az adatcímkét alapértelmezés szerint rejtetté teszi a DefaultDataLabelFormat tulajdonság minden Show*-flagjának (ShowValue, ...) hamis állapotra állításával. Az IsVisible ezután hamis lesz.

--------------------

Ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), akkor a DefaultDataLabelFormat tulajdonság Show*-flagjaival (ShowValue, ...) true állapotra állításával tehető "alapértelmezés szerint láthatóvá".

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

Adatcímkék vezetővonal formátumát képviseli. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | Megkeresendő DataLabel. |

**Visszatér:**
int - A DataLabel indexe, vagy -1, ha a DataLabel nem ebben a gyűjteményben van.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Lekéri a megadott indexű adatpont adatcímkéjét.

--------------------

Az adatcímke elérésének alternatív módja: - series.getDataPoints().get\_Item(i).getLabel() - címke tulajdonságok kezelése.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Lekéri vagy beállítja az adatcímkék alapértelmezett alakzat típusát. [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) értéket ad vissza, ha nincs definiált alakzat.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Állítsa be az első sorozat összes adatcímkéjének alakzat típusát Ellipse-re.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Ennek a tulajdonságnak a beállítása ugyancsak beállítja az IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) tulajdonságot az összes adatcímkére a gyűjteményben ugyanarra az értékre.

**Visszatér:**
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Lekéri vagy beállítja az adatcímkék alapértelmezett alakzat típusát. [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) értéket ad vissza, ha nincs definiált alakzat.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Állítsa be az első sorozat összes adatcímkéjének alakzat típusát Ellipse-re.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Ennek a tulajdonságnak a beállítása ugyancsak beállítja az IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) tulajdonságot az összes adatcímkére a gyűjteményben ugyanarra az értékre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diát. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)