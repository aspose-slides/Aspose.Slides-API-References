---
title: IDataLabel
second_title: Aspose.Slides Androidhoz a Java API hivatkozás alapján
description: Egy sorozat címkéit képviseli.
type: docs
url: /hu/com.aspose.slides/idatalabel/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Egy sorozat címkéit képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isVisible()](#isVisible--) | A False azt jelenti, hogy az adatcímke nem látható (és ezért minden Show\*-flags (ShowValue, ...) false). |
| [hide()](#hide--) | Elrejti az adatcímkét az összes Show\*-flags (ShowValue, ...) false állapotra állításával. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Visszaadja az adatcímke formátumát. |
| [getValueFromCell()](#getValueFromCell--) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [getActualLabelText()](#getActualLabelText--) | Visszaadja a tényleges címkeszöveget a DataLabelFormat beállításai vagy a TextFrameForOverriding.Text értéke alapján. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

A False azt jelenti, hogy az adatcímke nem látható (és ezért minden Show\*-flags (ShowValue, ...) false). Csak olvasható boolean.

--------------------

Ha az adatcímke látható, a Hide() metódussal elrejtheti. De ha az adatcímke nem látható (IsVisible false), a Show\*-flags (ShowValue, ...) true állapotra állításával láthatóvá teheti.

**Visszatérési érték:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Elrejti az adatcímkét az összes Show\*-flags (ShowValue, ...) false állapotra állításával. Az IsVisible ezután false lesz.

--------------------

Ha az adatcímke nem látható (IsVisible false), a Show\*-flags (ShowValue, ...) true állapotra állításával láthatóvá tehető.

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

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság true értékre van állítva.

**Visszatérési érték:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság true értékre van állítva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Visszaadja a tényleges címkeszöveget a DataLabelFormat beállításai vagy a TextFrameForOverriding.Text értéke alapján.

**Visszatérési érték:**
java.lang.String - Aktuális címke szöveg String