---
title: DataLabel
second_title: Aspose.Slides Java API Referencia
description: Sorozat címkéket képvisel.
type: docs
url: /hu/com.aspose.slides/datalabel/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

Egy sorozat címkéit képviseli.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | Létrehoz egy új DataLabel példányt. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [isVisible()](#isVisible--) | A False azt jelenti, hogy a címke nem látható (és ezért az összes Show*-flag (ShowValue, …) hamis). |
| [hide()](#hide--) | Elrejti a címkét az összes Show*-flag (ShowValue, …) hamis állapotra állításával. |
| [getActualLabelText()](#getActualLabelText--) | Visszaadja a tényleges címkeszöveget a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding-et a “text” paraméterben megadott szöveggel. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tartalmazhat gazdag formázott szöveget. |
| [getTextFormat()](#getTextFormat--) | Visszaadja a szövegformátumot. |
| [getX()](#getX--) | Visszaadja vagy beállítja a címke x koordinátáját a diagram szélességének hányadában. |
| [setX(float value)](#setX-float-) | Visszaadja vagy beállítja a címke x koordinátáját a diagram szélességének hányadában. |
| [getY()](#getY--) | Visszaadja vagy beállítja a címke y koordinátáját a diagram magasságának hányadában. |
| [setY(float value)](#setY-float-) | Visszaadja vagy beállítja a címke y koordinátáját a diagram magasságának hányadában. |
| [getWidth()](#getWidth--) | Visszaadja vagy beállítja a címke szélességét a diagram szélességének hányadában. |
| [setWidth(float value)](#setWidth-float-) | Visszaadja vagy beállítja a címke szélességét a diagram szélességének hányadában. |
| [getHeight()](#getHeight--) | Visszaadja vagy beállítja a címke magasságát a diagram magasságának hányadában. |
| [setHeight(float value)](#setHeight-float-) | Visszaadja vagy beállítja a címke magasságát a diagram magasságának hányadában. |
| [getRight()](#getRight--) | Jobb. |
| [getBottom()](#getBottom--) | Alul. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Visszaadja a címkeformátumot. |
| [getValueFromCell()](#getValueFromCell--) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [getActualX()](#getActualX--) | Meghatározza a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest. |
| [getActualY()](#getActualY--) | Meghatározza a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. |
| [getActualWidth()](#getActualWidth--) | Meghatározza a diagram elem tényleges szélességét. |
| [getActualHeight()](#getActualHeight--) | Meghatározza a diagram elem tényleges magasságát. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diát. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációját. |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```

Létrehoz egy új DataLabel példányt.

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

A False azt jelenti, hogy a címke nem látható (és ezért az összes Show*-flag (ShowValue, …) hamis). Csak olvasható boolean.

--------------------

Ha a címke látható, a Hide() metódussal elrejthető. Ha a címke nem látható (IsVisible hamis), a Show*-flag-ek (ShowValue, …) true állapotra állításával láthatóvá tehető.

**Visszatérési érték:**
boolean
### hide() {#hide--}
```
public final void hide()
```

Elrejti a címkét az összes Show*-flag (ShowValue, …) hamis állapotra állításával. Az IsVisible ezután hamis lesz.

--------------------

Ha a címke nem látható (IsVisible hamis), a Show*-flag-ek (ShowValue, …) true állapotra állításával láthatóvá tehető.

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```

Visszaadja a tényleges címkeszöveget a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján.

**Visszatérési érték:**
java.lang.String - The java.lang.String object.
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializálja a TextFrameForOverriding-et a “text” paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, egyszerűen megváltoztatja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Szöveg az új TextFrameForOverriding-hez. |

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveg felülírja a címke automatikusan generált szövegét. Az automatikusan generált szöveg a ShowSeriesName, ShowValue, … tulajdonságok által kezelt szöveg, amely a TextFormatManager.TextFormat tulajdonsággal formázott. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

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

Visszaadja vagy beállítja a címke x koordinátáját a diagram szélességének hányadában. Olvasás/írás float.

**Visszatérési érték:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Visszaadja vagy beállítja a címke x koordinátáját a diagram szélességének hányadában. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Visszaadja vagy beállítja a címke y koordinátáját a diagram magasságának hányadában. Olvasás/írás float.

**Visszatérési érték:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Visszaadja vagy beállítja a címke y koordinátáját a diagram magasságának hányadában. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Visszaadja vagy beállítja a címke szélességét a diagram szélességének hányadában. Olvasás/írás float.

**Visszatérési érték:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Visszaadja vagy beállítja a címke szélességét a diagram szélességének hányadában. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Visszaadja vagy beállítja a címke magasságát a diagram magasságának hányadában. Olvasás/írás float.

**Visszatérési érték:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Visszaadja vagy beállítja a címke magasságát a diagram magasságának hányadában. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

Jobb. Csak olvasható float.

**Visszatérési érték:**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```

Alul. Csak olvasható float.

**Visszatérési érték:**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```

Visszaadja a címkeformátumot. Csak olvasható [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatérési érték:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazandó, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság értéke true.

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazandó, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság értéke true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Meghatározza a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

Meghatározza a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

Meghatározza a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

Meghatározza a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. Olvasás float.

**Visszatérési érték:**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diát. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)