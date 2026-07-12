---
title: Background
second_title: Aspose.Slides for Android Java API referencia
description: A dia háttérét képviseli.
type: docs
url: /hu/com.aspose.slides/background/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

A diák háttérét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Visszaad egy háttérkitöltés típusát. |
| [setType(byte value)](#setType-byte-) | Visszaad egy háttérkitöltés típusát. |
| [getFillFormat()](#getFillFormat--) | Visszaad egy FillFormat objektumot a BackgroundType.OwnBackground kitöltéshez. |
| [getEffectFormat()](#getEffectFormat--) | Visszaad egy EffectFormat objektumot a BackgroundType.OwnBackground kitöltéshez. |
| [getStyleColor()](#getStyleColor--) | Visszaad egy ColorFormat objektumot egy BackgroundType.Themed kitöltéshez. |
| [getStyleIndex()](#getStyleIndex--) | Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér témagyűjteményben. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér témagyűjteményben. |
| [getEffective()](#getEffective--) | Megkapja a hatékony háttéradatokat az öröklődés alkalmazása után. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Visszaad a forma szülődiáját. |
| [getPresentation()](#getPresentation--) | Visszaad a dia szülő prezentációját. |
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

Visszaad egy FillFormat objektumot a BackgroundType.OwnBackground kitöltéshez. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Visszaad egy EffectFormat objektumot a BackgroundType.OwnBackground kitöltéshez. Csak olvasható [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Visszatér:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Visszaad egy ColorFormat objektumot egy BackgroundType.Themed kitöltéshez. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér témagyűjteményben. 0 jelentése nincs kitöltés. 1..999 – index. Olvasás/írás int.

**Visszatér:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Visszaad egy indexet a BackgroundType.Themed kitöltéshez a háttér témagyűjteményben. 0 jelentése nincs kitöltés. 1..999 – index. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Megkapja a hatékony háttéradatokat az öröklődés alkalmazása után.

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

Verzió. Csak olvasható long.

**Visszatér:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaad a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Visszaad a forma szülő diáját. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Visszaad a dia szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[Presentation](../../com.aspose.slides/presentation)