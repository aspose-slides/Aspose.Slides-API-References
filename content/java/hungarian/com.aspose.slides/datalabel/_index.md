---
title: DataLabel
second_title: Aspose.Slides Java API referencia
description: Sorozat címkéket képvisel.
type: docs
url: /hu/com.aspose.slides/datalabel/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

A sorozat címkéket képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Létrehozza a DataLabel osztály egy új példányát. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatel címke nem látható (és így minden Show*-jelző (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatel címkét rejtetté teszi az összes Show*-jelző (ShowValue, ...) hamis állapotúra állításával. |
| [getActualLabelText()](#getActualLabelText--) | Visszaadja a címke tényleges szövegét a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding-ot a "text" paraméterben megadott szöveggel. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tartalmazhat gazdag formázott szöveget. |
| [getTextFormat()](#getTextFormat--) | Visszaadja a szövegformátumot. |
| [getX()](#getX--) | Visszaadja vagy beállítja a cím X koordinátáját a diagram szélességének hányadában. |
| [setX(float value)](#setX-float-) | Visszaadja vagy beállítja a cím X koordinátáját a diagram szélességének hányadában. |
| [getY()](#getY--) | Visszaadja vagy beállítja a cím Y koordinátáját a diagram magasságának hányadában. |
| [setY(float value)](#setY-float-) | Visszaadja vagy beállítja a cím Y koordinátáját a diagram magasságának hányadában. |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja a cím szélességét a diagram szélességének hányadában. |
| [setWidth(float value)](#setWidth-float-) | Visszaadja vagy beállítja a cím szélességét a diagram szélességének hányadában. |
| [getHeight()](#getHeight--) | Visszaadja vagy beállítja a cím magasságát a diagram magasságának hányadában. |
| [setHeight(float value)](#setHeight-float-) | Visszaadja vagy beállítja a cím magasságát a diagram magasságának hányadában. |
| [getRight()](#getRight--) | Jobb. |
| [getBottom()](#getBottom--) | Alsó. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Visszaadja az adatel címke formátumát. |
| [getValueFromCell()](#getValueFromCell--) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [getLabelShapeType()](#getLabelShapeType--) | Lekéri vagy beállítja az adatel címke alakzat típusát. |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | Lekéri vagy beállítja az adatel címke alakzat típusát. |
| [getActualX()](#getActualX--) | Megadja a diagram elem tényleges X helyét (bal), a diagram bal felső sarkához képest. |
| [getActualY()](#getActualY--) | Megadja a diagram elem tényleges tetejét a diagram bal felső sarkához képest. |
| [getActualWidth()](#getActualWidth--) | Megadja a diagram elem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Megadja a diagram elem tényleges magasságát. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diaját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációját. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```


Létrehozza a DataLabel osztály egy új példányát.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Szülő ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


Visszaadja a szülő diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


A hamis azt jelenti, hogy az adatel címke nem látható (és így minden Show*-jelző (ShowValue, ...) hamis). Csak olvasható boolean.

--------------------

Ha az adatel címke látható, elrejtheted a Hide() metódussal. Ha azonban az adatel címke nem látható (IsVisible hamis), láthatóvá teheted a Show*-jelzők (ShowValue, ...) true állapotra állításával.

**Visszatérési érték:**
boolean
### hide() {#hide--}
```
public final void hide()
```


Az adatel címkét rejtetté teszi az összes Show*-jelző (ShowValue, ...) hamis állapotúra állításával. Ennek hatására az IsVisible hamis lesz.

--------------------

Ha az adatel címke nem látható (IsVisible hamis), láthatóvá teheted a Show*-jelzők (ShowValue, ...) true állapotra állításával.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```


Visszaadja a címke tényleges szövegét a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján.

**Visszatérési érték:**
java.lang.String - A java.lang.String objektum.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


Inicializálja a TextFrameForOverriding-ot a "text" paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen módosítja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Az új TextFrameForOverriding szövege. |

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveg felülírja a címke automatikusan generált szövegét. Az automatikusan generált szöveg a ShowSeriesName, ShowValue, ... tulajdonságok által kezelt szöveget jelenti, és a TextFormatManager.TextFormat tulajdonsággal van formázva. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Visszaadja a szövegformátumot. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatérési érték:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```


Visszaadja vagy beállítja a cím X koordinátáját a diagram szélességének hányadában. Olvasás/írás float .

**Visszatérési érték:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


Visszaadja vagy beállítja a cím X koordinátáját a diagram szélességének hányadában. Olvasás/írás float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```


Visszaadja vagy beállítja a cím Y koordinátáját a diagram magasságának hányadában. Olvasás/írás float .

**Visszatérési érték:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


Visszaadja vagy beállítja a cím Y koordinátáját a diagram magasságának hányadában. Olvasás/írás float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```


Visszaadja vagy beállítja a cím szélességét a diagram szélességének hányadában. Olvasás/írás float .

**Visszatérési érték:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


Visszaadja vagy beállítja a cím szélességét a diagram szélességének hányadában. Olvasás/írás float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


Visszaadja vagy beállítja a cím magasságát a diagram magasságának hányadában. Olvasás/írás float .

**Visszatérési érték:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


Visszaadja vagy beállítja a cím magasságát a diagram magasságának hányadában. Olvasás/írás float .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```


Jobb. Csak olvasható float .

**Visszatérési érték:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


Alsó. Csak olvasható float .

**Visszatérési érték:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```


Visszaadja az adatel címke formátumát. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatérési érték:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```


Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazható, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz.

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```


Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazható, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```


Lekéri vagy beállítja az adatel címke alakzat típusát. Ha nincs meghatározott alakzat, akkor [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined).

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

**Visszatérési érték:**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public final void setLabelShapeType(int value)
```


Lekéri vagy beállítja az adatel címke alakzat típusát. Ha nincs meghatározott alakzat, akkor [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined).

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
### getActualX() {#getActualX--}
```
public final float getActualX()
```


Megadja a diagram elem tényleges X helyét (bal) a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Megadja a diagram elem tényleges tetejét a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Megadja a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Megadja a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Visszaadja a FillFormat szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)