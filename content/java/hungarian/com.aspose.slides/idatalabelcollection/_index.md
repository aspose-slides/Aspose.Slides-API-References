---
title: IDataLabelCollection
second_title: Aspose.Slides Java API-referencia
description: Sorozat címkéket képvisel.
type: docs
url: /hu/com.aspose.slides/idatalabelcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Sorozat címkéket képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű adatpont adatcímkéjét. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Visszaadja az összes adatcímke alapértelmezett formátumát a gyűjteményben. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Adatcímkék vezetővonalainak formátumát képviseli. |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és így a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). |
| [hide()](#hide--) | Alapértelmezés szerint elrejti az adatcímkét az összes Show*-jelző (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban hamis állapotba állításával. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lekéri a gyűjteményben lévő látható adatcímkék számát. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben lévő összes adatcímke számát. |
| [getParentSeries()](#getParentSeries--) | Visszaadja a szülő diagram sorozatot. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Lekéri vagy beállítja az adatcímkék alapértelmezett alakzattípusát. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Lekéri vagy beállítja az adatcímkék alapértelmezett alakzattípusát. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Lekéri a megadott indexű adatpont adatcímkéjét.

--------------------

Az adatcímke alternatív elérése: - getSeries().getDataPoints().get_Item(i).getLabel() - címke tulajdonságok kezelése.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Visszaadja az összes adatcímke alapértelmezett formátumát a gyűjteményben. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatérési érték:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Adatcímkék vezetővonalainak formátumát képviseli. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és így a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). Csak olvasható  boolean .

--------------------

Ha az adatcímke alapértelmezés szerint látható, a Hide() metódussal alapértelmezés szerint elrejtheted. Ha az adatcímke nem látható alapértelmezés szerint (IsVisible hamis), a Show*-jelzők (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban true állapotra állításával teheted láthatóvá alapértelmezés szerint.

**Visszatérési érték:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Alapértelmezés szerint elrejti az adatcímkét az összes Show*-jelző (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban hamis állapotba állításával. Az IsVisible ezután hamis lesz.

--------------------

Ha az adatcímke nem látható alapértelmezés szerint (IsVisible hamis), a Show*-jelzők (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban true állapotra állításával teheted láthatóvá alapértelmezés szerint.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Lekéri a gyűjteményben lévő látható adatcímkék számát. Csak olvasható  int .

**Visszatérési érték:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben lévő összes adatcímke számát. Csak olvasható  int .

**Visszatérési érték:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Visszaadja a szülő diagram sorozatot. Csak olvasható [IChartSeries](../../com.aspose.slides/ichartseries).

**Visszatérési érték:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Visszaadja a megadott DataLabel indexét a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | A keresett DataLabel. |

**Visszatérési érték:**
int - A DataLabel indexe vagy -1, ha a DataLabel nem ebbe a gyűjteménybe tartozik.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

Lekéri vagy beállítja az adatcímkék alapértelmezett alakzattípusát. [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) visszatér, ha nincs definiálva alakzat.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Állítsa be az összes adatcímke alakzattípusát az első sorozatban Ellipse-re.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Ennek a tulajdonságnak a beállítása szintén beállítja az IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) tulajdonságot minden adatcímkénál a gyűjteményben ugyanarra az értékre.

**Visszatérési érték:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

Lekéri vagy beállítja az adatcímkék alapértelmezett alakzattípusát. [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) visszatér, ha nincs definiálva alakzat.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Állítsa be az összes adatcímke alakzattípusát az első sorozatban Ellipse-re.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Ennek a tulajdonságnak a beállítása szintén beállítja az IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) tulajdonságot minden adatcímkénál a gyűjteményben ugyanarra az értékre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |