---
title: LegendEntryProperties
second_title: Aspose.Slides Java API referencia
description: A diagram jelmagyarázatának tulajdonságait reprezentálja.
type: docs
url: /hu/com.aspose.slides/legendentryproperties/
---
**Öröklődés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

A diagram jelmagyarázatának tulajdonságait reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | Visszaadja a szövegformátumot. |
| [getHide()](#getHide--) | Megállapítja, hogy a jelmagyarázat bejegyzése rejtve van-e. |
| [setHide(boolean value)](#setHide-boolean-) | Megállapítja, hogy a jelmagyarázat bejegyzése rejtve van-e. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő előadását. |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Visszaadja a szövegformátumot. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatér:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getHide() {#getHide--}
```
public final boolean getHide()
```


Megállapítja, hogy a jelmagyarázat bejegyzése rejtve van-e. Olvasás/írás boolean.

**Visszatér:**
boolean
### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```


Megállapítja, hogy a jelmagyarázat bejegyzése rejtve van-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


Visszaadja a szülő diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Visszaadja a FillFormat szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja a FillFormat szülő előadását. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)