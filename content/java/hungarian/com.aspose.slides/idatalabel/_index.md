---
title: IDataLabel
second_title: Aspose.Slides Java API referenciája
description: Sorozatcímkéket reprezentál.
type: docs
url: /hu/com.aspose.slides/idatalabel/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Egy sorozat címkéit reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke nem látható (és ezért minden Show\*-flag (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímkét elrejti, ha minden Show\*-flag (ShowValue, ...) értékét hamisra állítja. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Visszaadja az adatcímke formátumát. |
| [getValueFromCell()](#getValueFromCell--) | Lekérdezi vagy beállítja a munkafüzet adatcelláját. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lekérdezi vagy beállítja a munkafüzet adatcelláját. |
| [getActualLabelText()](#getActualLabelText--) | Visszaadja a tényleges címke szövegét a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján. |
| [getLabelShapeType()](#getLabelShapeType--) | Lekérdezi vagy beállítja az adatcímke alakzat típusát. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Lekérdezi vagy beállítja az adatcímke alakzat típusát. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

A hamis azt jelenti, hogy az adatcímke nem látható (és ezért minden Show\*-flag (ShowValue, ...) hamis). Írásvédett logikai érték.

--------------------

Ha az adatcímke látható, a Hide() metódussal elrejtheti. Ha azonban az adatcímke nem látható (IsVisible hamis), a Show\*-flag (ShowValue, ...) értékét true állapotra állítva láthatóvá tehető.

**Visszatérési érték:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Az adatcímkét elrejti, ha minden Show\*-flag (ShowValue, ...) értékét hamisra állítja. Ez után az IsVisible hamis lesz.

--------------------

Ha az adatcímke nem látható (IsVisible hamis), a Show\*-flag (ShowValue, ...) értékét true állapotra állítva láthatóvá tehető.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Visszaadja az adatcímke formátumát. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatérési érték:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Lekérdezi vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz.

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Lekérdezi vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Visszaadja a tényleges címke szövegét a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján.

**Visszatérési érték:**
java.lang.String - Aktuális címke szöveg
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

Lekérdezi vagy beállítja az adatcímke alakzat típusát. Ha nincs meghatározva alakzat, [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) értéket ad vissza.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Beállítja az első adatcímke alakzattípusát Ellipse-re.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

Lekérdezi vagy beállítja az adatcímke alakzat típusát. Ha nincs meghatározva alakzat, [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) értéket ad vissza.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Állítsa be az első adatcímke alakzattípusát Ellipse-re.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |