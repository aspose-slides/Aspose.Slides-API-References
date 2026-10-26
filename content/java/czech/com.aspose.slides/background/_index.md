---
title: Background
second_title: Aspose.Slides pro Java – reference API
description: Zastupuje pozadí snímku.
type: docs
url: /cs/com.aspose.slides/background/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Zastupuje pozadí snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Vrací typ výplně pozadí. |
| [setType(byte value)](#setType-byte-) | Vrací typ výplně pozadí. |
| [getFillFormat()](#getFillFormat--) | Vrací FillFormat pro výplň BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Vrací EffectFormat pro výplň BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Vrací ColorFormat pro výplň BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. |
| [getEffective()](#getEffective--) | Získá efektivní data pozadí s aplikovanou dědičností. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek tvaru. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci snímku. |
### getType() {#getType--}
```
public final byte getType()
```

Vrací typ výplně pozadí. Číst/Zapisovat [BackgroundType](../../com.aspose.slides/backgroundtype).

**Vrací:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Vrací typ výplně pozadí. Číst/Zapisovat [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Vrací FillFormat pro výplň BackgroundType.OwnBackground. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Vrací EffectFormat pro výplň BackgroundType.OwnBackground. Pouze pro čtení [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Vrací:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Vrací ColorFormat pro výplň BackgroundType.Themed. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. 0 znamená žádnou výplň. 1..999 – index. Číst/Zapisovat int.

**Vrací:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Vrací index výplně BackgroundType.Themed ve sbírce motivů pozadí. 0 znamená žádnou výplň. 1..999 – index. Číst/Zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Získá efektivní data pozadí s aplikovanou dědičností.

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

**Vrací:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent\_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Vrací nadřazený snímek tvaru. Pouze pro čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Vrací nadřazenou prezentaci snímku. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[Presentation](../../com.aspose.slides/presentation)