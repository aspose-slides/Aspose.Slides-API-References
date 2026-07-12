---
title: IDataLabelCollection
second_title: Aspose.Slides for Android via Java API Referenciája
description: Egy sorozat címkéit képviseli.
type: docs
url: /hu/com.aspose.slides/idatalabelcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Egy sorozat címkéit képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexű adatpont adatcímkéjét. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Visszatér az összes adatcímke alapértelmezett formátumával a gyűjteményben. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Az adatcímkék vezetővonalainak formátumát képviseli. |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímkét alapértelmezés szerint rejtetté teszi a DefaultDataLabelFormat tulajdonság összes Show*-jelzőjének (ShowValue, ...) hamis állapotra állításával. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lekéri a látható adatcímkék számát a gyűjteményben. |
| [getCount()](#getCount--) | Lekéri az összes adatcímke számát a gyűjteményben. |
| [getParentSeries()](#getParentSeries--) | Visszatér a szülő diagram sorozattal. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Visszatér a megadott DataLabel indexével a gyűjteményben. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Lekéri a megadott indexű adatpont adatcímkéjét.

--------------------

Az adatcímke elérésének alternatív módja: - getSeries().getDataPoints().get_Item(i).getLabel() - címke tulajdonságok kezelése.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Visszatér az összes adatcímke alapértelmezett formátumával a gyűjteményben. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatér:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Az adatcímkék vezetővonalainak formátumát képviseli. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és ezért a DefaultDataLabelFormat tulajdonság összes Show*-jelzője (ShowValue, ...) hamis). Csak olvasható  boolean .

--------------------

Ha az adatcímke alapértelmezés szerint látható, a Hide() metódussal alapértelmezés szerint rejtetté tehető. Ha azonban az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), a DefaultDataLabelFormat tulajdonság Show*-jelzőinek (ShowValue, ...) igaz állapotra állításával „alapértelmezés szerint látható”-vá tehető.

**Visszatér:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Az adatcímkét alapértelmezés szerint rejtetté teszi a DefaultDataLabelFormat tulajdonság összes Show*-jelzőjének (ShowValue, ...) hamis állapotra állításával. Az IsVisible ezután hamis lesz.

--------------------

Ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), a DefaultDataLabelFormat tulajdonság Show*-jelzőinek (ShowValue, ...) igaz állapotra állításával „alapértelmezés szerint látható”-vá tehető.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Lekéri a látható adatcímkék számát a gyűjteményben. Csak olvasható  int .

**Visszatér:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Lekéri az összes adatcímke számát a gyűjteményben. Csak olvasható  int .

**Visszatér:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Visszatér a szülő diagram sorozattal. Csak olvasható [IChartSeries](../../com.aspose.slides/ichartseries).

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Visszatér a megadott DataLabel indexével a gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | A keresett DataLabel. |

**Visszatér:**
int - A DataLabel indexe vagy -1, ha a DataLabel nem ebből a gyűjteményből származik.