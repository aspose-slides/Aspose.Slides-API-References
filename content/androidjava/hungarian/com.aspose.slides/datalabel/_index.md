---
title: DataLabel
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy sorozat címkéit jelöli.
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

A sorozat címkéit jelöli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Létrehoz egy új DataLabel osztály példányt. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszatér a szülő diagrammal. |
| [isVisible()](#isVisible--) | A hamis érték azt jelenti, hogy az adatcímke nem látható (és így minden Show*-jelző (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímke elrejtése az összes Show*-jelző (ShowValue, ...) hamis állapotra állításával. |
| [getActualLabelText()](#getActualLabelText--) | Visszatér a tényleges címkeszöveggel a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding-t a „text” paraméterben megadott szöveggel. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tartalmazhat gazdag formázott szöveget. |
| [getTextFormat()](#getTextFormat--) | Visszatér a szövegformátummal. |
| [getX()](#getX--) | Visszatér vagy beállítja a cím x-koordinátáját a diagram szélességének arányában. |
| [setX(float value)](#setX-float-) | Visszatér vagy beállítja a cím x-koordinátáját a diagram szélességének arányában. |
| [getY()](#getY--) | Visszatér vagy beállítja a cím y-koordinátáját a diagram magasságának arányában. |
| [setY(float value)](#setY-float-) | Visszatér vagy beállítja a cím y-koordinátáját a diagram magasságának arányában. |
| [getWidth()](#getWidth--) | Visszatér vagy beállítja a cím szélességét a diagram szélességének arányában. |
| [setWidth(float value)](#setWidth-float-) | Visszatér vagy beállítja a cím szélességét a diagram szélességének arányában. |
| [getHeight()](#getHeight--) | Visszatér vagy beállítja a cím magasságát a diagram magasságának arányában. |
| [setHeight(float value)](#setHeight-float-) | Visszatér vagy beállítja a cím magasságát a diagram magasságának arányában. |
| [getRight()](#getRight--) | Jobb. |
| [getBottom()](#getBottom--) | Alsó. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Visszatér az adatcímke formátummal. |
| [getValueFromCell()](#getValueFromCell--) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [getActualX()](#getActualX--) | Meghatározza a diagramelem tényleges x-helyzetét (bal) a diagram bal felső sarkához viszonyítva. |
| [getActualY()](#getActualY--) | Meghatározza a diagramelem tényleges felső pozícióját a diagram bal felső sarkához viszonyítva. |
| [getActualWidth()](#getActualWidth--) | Meghatározza a diagramelem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Meghatározza a diagramelem tényleges magasságát. |
| [getSlide()](#getSlide--) | Visszatér a FillFormat szülő diavetítésével. |
| [getPresentation()](#getPresentation--) | Visszatér a FillFormat szülő prezentációjával. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Létrehoz egy új DataLabel osztály példányt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Szülő ChartDataPoint. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszatér a szülő diagrammal. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

A hamis érték azt jelenti, hogy az adatcímke nem látható (és így minden Show*-jelző (ShowValue, ...) hamis). Csak olvasható boolean.

--------------------

Ha az adatcímke látható, elrejtheti a Hide() metódussal. Ha az adatcímke nem látható (IsVisible hamis), a Show*-jelzők (ShowValue, ...) igaz állapotra állításával láthatóvá tehető.

**Visszatér:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Az adatcímke elrejtése az összes Show*-jelző (ShowValue, ...) hamis állapotra állításával. Ezután az IsVisible hamis lesz.

--------------------

Ha az adatcímke nem látható (IsVisible hamis), a Show*-jelzők (ShowValue, ...) igaz állapotra állításával láthatóvá tehető.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Visszatér a tényleges címkeszöveggel a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján.

**Visszatér:**
java.lang.String - A java.lang.String objektum.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializálja a TextFrameForOverriding-t a „text” paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, egyszerűen módosítja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Szöveg az új TextFrameForOverriding-hez. |

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveg felülírja az adatcímke automatikusan generált szövegét. Az automatikusan generált szöveg a ShowSeriesName, ShowValue, … tulajdonságok által kezelt szöveg, amely a TextFormatManager.TextFormat tulajdonsággal formázott. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Visszatér a szövegformátummal. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatér:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```

Visszatér vagy beállítja a cím x-koordinátáját a diagram szélességének arányában. Olvasható/írható float.

**Visszatér:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Visszatér vagy beállítja a cím x-koordinátáját a diagram szélességének arányában. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Visszatér vagy beállítja a cím y-koordinátáját a diagram magasságának arányában. Olvasható/írható float.

**Visszatér:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Visszatér vagy beállítja a cím y-koordinátáját a diagram magasságának arányában. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Visszatér vagy beállítja a cím szélességét a diagram szélességének arányában. Olvasható/írható float.

**Visszatér:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Visszatér vagy beállítja a cím szélességét a diagram szélességének arányában. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Visszatér vagy beállítja a cím magasságát a diagram magasságának arányában. Olvasható/írható float.

**Visszatér:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Visszatér vagy beállítja a cím magasságát a diagram magasságának arányában. Olvasható/írható float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Jobb. Csak olvasható float.

**Visszatér:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Alsó. Csak olvasható float.

**Visszatér:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Visszatér az adatcímke formátummal. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatér:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazandó, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz.

**Visszatér:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazandó, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Meghatározza a diagramelem tényleges x-helyzetét (bal) a diagram bal felső sarkához viszonyítva. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Meghatározza a diagramelem tényleges felső pozícióját a diagram bal felső sarkához viszonyítva. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Meghatározza a diagramelem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Meghatározza a diagramelem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Csak olvasható float.

**Visszatér:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszatér a FillFormat szülő diavetítésével. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszatér a FillFormat szülő prezentációjával. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)