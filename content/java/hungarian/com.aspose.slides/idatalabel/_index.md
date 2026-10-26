---
title: IDataLabel
second_title: Aspose.Slides Java API-referencia
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
| [isVisible()](#isVisible--) | A hamis azt jelenti, hogy az adatcímke nem látható (és ezért minden Show*-jelző (ShowValue, ...) hamis). |
| [hide()](#hide--) | Az adatcímkét elrejti az összes Show*-jelző (ShowValue, ...) hamis állapotba állításával. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Visszaadja az adatcímke formátumát. |
| [getValueFromCell()](#getValueFromCell--) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Lekéri vagy beállítja a munkafüzet adatcelláját. |
| [getActualLabelText()](#getActualLabelText--) | Visszaadja a tényleges címkeszöveget a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

A hamis azt jelenti, hogy az adatcímke nem látható (és ezért minden Show*-jelző (ShowValue, ...) hamis). **Csak olvasható** boolean.

--------------------

Ha az adatcímke látható, a Hide() metódussal elrejtheti. Ha az adatcímke nem látható (IsVisible hamis), akkor a Show*-jelzők (ShowValue, ...) true állapotba állításával láthatóvá tehető.

**Visszatér:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Az adatcímkét elrejti az összes Show*-jelző (ShowValue, ...) hamis állapotba állításával. Ezután az IsVisible hamis lesz.

--------------------

Ha az adatcímke nem látható (IsVisible hamis), akkor a Show*-jelzők (ShowValue, ...) true állapotba állításával láthatóvá tehető.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Visszaadja az adatcímke formátumát. **Csak olvasható** [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Visszatér:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság true.

**Visszatér:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Visszaadja a tényleges címkeszöveget a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján.

**Visszatér:**
java.lang.String - A tényleges címkeszöveg String