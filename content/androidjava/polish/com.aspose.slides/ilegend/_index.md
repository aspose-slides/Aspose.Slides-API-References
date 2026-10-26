---
title: ILegend
second_title: Aspose.Slides dla Androida poprzez odniesienie Java API
description: Reprezentuje właściwości legendy wykresu.
type: docs
url: /pl/com.aspose.slides/ilegend/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Reprezentuje właściwości legendy wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOverlay()](#getOverlay--) | Określa, czy inne elementy wykresu mogą nakładać się na legendę. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Określa, czy inne elementy wykresu mogą nakładać się na legendę. |
| [getPosition()](#getPosition--) | Określa pozycję legendy na wykresie. |
| [setPosition(int value)](#setPosition-int-) | Określa pozycję legendy na wykresie. |
| [getFormat()](#getFormat--) | Zwraca format legendy. |
| [getEntries()](#getEntries--) | Pobiera wpisy legendy. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Określa, czy inne elementy wykresu mogą nakładać się na legendę. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Określa, czy inne elementy wykresu mogą nakładać się na legendę. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Określa pozycję legendy na wykresie. Wartości nie-NaN właściwości X, Y, Width, Heigt zastępują działanie tej właściwości. Odczyt/zapis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Określa pozycję legendy na wykresie. Wartości nie-NaN właściwości X, Y, Width, Heigt zastępują działanie tej właściwości. Odczyt/zapis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Zwraca format legendy. Tylko do odczytu [IFormat](../../com.aspose.slides/iformat).

**Zwraca:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Pobiera wpisy legendy. Tylko do odczytu [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Zwraca:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)