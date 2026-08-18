---
title: IDataLabelCollection
second_title: Aspose.Slides Java API Referencia
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
| [get_Item(int index)](#get-Item-int-) | Lekérdezi a megadott indexű adatpont adatcímkéjét. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Visszaadja az összes adatcímke alapértelmezett formátumát a gyűjteményben. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | A data címkék vezetővonalainak formátumát képviseli. |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és így a DefaultDataLabelFormat tulajdonság összes Show\*-jelzője (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímkét alapértelmezés szerint rejtetté teszi az összes Show\*-jelző (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban false állapotra állításával. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Lekérdezi a látható adatcímkék számát a gyűjteményben. |
| [getCount()](#getCount--) | Lekérdezi az összes adatcímke számát a gyűjteményben. |
| [getParentSeries()](#getParentSeries--) | Visszaadja a szülő diagram sorozatot. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Visszaadja a megadott DataLabel indexét a gyűjteményben. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Lekérdezi a megadott indexű adatpont adatcímkéjét.

--------------------

Az adatcímke elérésének alternatív módja:
- getSeries().getDataPoints().get\_Item(i).getLabel()
- címke tulajdonságainak kezelése.

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

A data címkék vezetővonalak formátumát képviseli. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

A hamis azt jelenti, hogy az adatcímke alapértelmezés szerint nem látható (és így a DefaultDataLabelFormat tulajdonság összes Show\*-jelzője (ShowValue, ...) hamis). Csak olvasható  boolean .

--------------------

Ha az adatcímke alapértelmezés szerint látható, a Hide() metódussal tehető alapértelmezés szerint rejtetté. De ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), a Show\*-jelzők (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban true állapotba állításával tehető "alapértelmezés szerint láthatóvá".

**Visszatérési érték:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Az adatcímkét alapértelmezés szerint rejtetté teszi az összes Show\*-jelző (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban false állapotra állításával. Az IsVisible hamis lesz ezután.

--------------------

Ha az adatcímke alapértelmezés szerint nem látható (IsVisible hamis), a Show\*-jelzők (ShowValue, ...) a DefaultDataLabelFormat tulajdonságban true állapotba állításával tehető "alapértelmezés szerint láthatóvá".

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Lekérdezi a látható adatcímkék számát a gyűjteményben. Csak olvasható  int .

**Visszatérési érték:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekérdezi az összes adatcímke számát a gyűjteményben. Csak olvasható  int .

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
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | A keresendő DataLabel. |

**Visszatérési érték:**
int - A DataLabel indexe vagy -1, ha a DataLabel nem ebből a gyűjteményből származik.