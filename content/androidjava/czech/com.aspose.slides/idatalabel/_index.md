---
title: IDataLabel
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje popisky řady.
type: docs
url: /cs/com.aspose.slides/idatalabel/
---
**Všechna implementovaná rozhraní:**  
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

Reprezentuje popisky řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [isVisible()](#isVisible--) | False znamená, že popisek dat není viditelný (a proto jsou všechny Show*-flags (ShowValue, ...) nastaveny na false). |
| [hide()](#hide--) | Skryjte popisek dat nastavením všech Show*-flags (ShowValue, ...) na false. |
| [getDataLabelFormat()](#getDataLabelFormat--) | Vrací formát popisku dat. |
| [getValueFromCell()](#getValueFromCell--) | Získá nebo nastaví buňku dat sešitu. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Získá nebo nastaví buňku dat sešitu. |
| [getActualLabelText()](#getActualLabelText--) | Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False znamená, že popisek dat není viditelný (a proto jsou všechny Show*-flags (ShowValue, ...) nastaveny na false). Pouze pro čtení boolean.

**Vrací:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Skryjte popisek dat nastavením všech Show*-flags (ShowValue, ...) na false. IsVisible bude po tomto nastavení false.

Pokud popisek dat není viditelný (IsVisible je false), můžete popisek dat zobrazit nastavením Show*-flags (ShowValue, ...) na true.

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Vrací formát popisku dat. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Získá nebo nastaví buňku dat sešitu. Použito, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Získá nebo nastaví buňku dat sešitu. Použito, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Vrací skutečný text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text.

**Vrací:**
java.lang.String - Skutečný text popisku String