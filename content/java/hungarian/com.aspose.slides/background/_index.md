---
title: Background
second_title: Aspose.Slides for Java API Referencia
description: A dia hátterét képviseli.
type: docs
url: /hu/com.aspose.slides/background/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden implementált interfész:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

A dia hátterét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaad egy háttérkitöltés típusát. |
| [setType(byte value)](#setType-byte-) | Visszaad egy háttérkitöltés típusát. |
| [getFillFormat()](#getFillFormat--) | Visszaad egy FillFormat-t a BackgroundType.OwnBackground kitöltéshez. |
| [getEffectFormat()](#getEffectFormat--) | Visszaad egy EffectFormat-t a BackgroundType.OwnBackground kitöltéshez. |
| [getStyleColor()](#getStyleColor--) | Visszaad egy ColorFormat-ot a BackgroundType.Themed kitöltéshez. |
| [getStyleIndex()](#getStyleIndex--) | Visszaad a BackgroundType.Themed kitöltés indexét a háttér témagyűjteményben. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Visszaad a BackgroundType.Themed kitöltés indexét a háttér témagyűjteményben. |
| [getEffective()](#getEffective--) | Megkapja a hatékony háttéradatokat az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Visszaad az alakzat szülő-diáját. |
| [getPresentation()](#getPresentation--) | Visszaad a dia szülő-prezentációját. |
### getType() {#getType--}
```
public final byte getType()
```

Visszaad egy háttérkitöltés típusát. Olvasás/írás [BackgroundType](../../com.aspose.slides/backgroundtype).

**Visszatér:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Visszaad egy háttérkitöltés típusát. Olvasás/írás [BackgroundType](../../com.aspose.slides/backgroundtype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Visszaad egy FillFormat-t a BackgroundType.OwnBackground kitöltéshez. Csak olvasás [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Visszaad egy EffectFormat-t a BackgroundType.OwnBackground kitöltéshez. Csak olvasás [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Visszaad egy ColorFormat-ot a BackgroundType.Themed kitöltéshez. Csak olvasás [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Visszaad a BackgroundType.Themed kitöltés indexét a háttér témagyűjteményben. 0 jelentése nincs kitöltés. 1..999 - index. Olvasás/írás int.

**Visszatér:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Visszaad a BackgroundType.Themed kitöltés indexét a háttér témagyűjteményben. 0 jelentése nincs kitöltés. 1..999 - index. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Megkapja a hatékony háttéradatokat az öröklődés alkalmazásával.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasás long.

**Visszatér:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad egy Parent_Immediate objektumot. Csak olvasás IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Visszaad egy alakzat szülő-diáját. Csak olvasás [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Visszaad egy dia szülő-prezentációját. Csak olvasás [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[Presentation](../../com.aspose.slides/presentation)