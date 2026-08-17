---
title: Background
second_title: Aspose.Slides für Java API-Referenz
description: Stellt den Hintergrund einer Folie dar.
type: docs
url: /de/com.aspose.slides/background/
---
**Vererbung:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Stellt den Hintergrund einer Folie dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt einen Typ der Hintergrundfüllung zurück. |
| [setType(byte value)](#setType-byte-) | Gibt einen Typ der Hintergrundfüllung zurück. |
| [getFillFormat()](#getFillFormat--) | Gibt ein FillFormat für die Hintergrundfüllung BackgroundType.OwnBackground zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt ein EffectFormat für die Hintergrundfüllung BackgroundType.OwnBackground zurück. |
| [getStyleColor()](#getStyleColor--) | Gibt ein ColorFormat für eine BackgroundType.Themed-Füllung zurück. |
| [getStyleIndex()](#getStyleIndex--) | Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. |
| [getEffective()](#getEffective--) | Liefert effektive Hintergrunddaten mit angewandter Vererbung. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer Form zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer Folie zurück. |

### getType() {#getType--}
```
public final byte getType()
```

Gibt einen Typ der Hintergrundfüllung zurück. Lesen/Schreiben [BackgroundType](../../com.aspose.slides/backgroundtype).

**Rückgabewert:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Gibt einen Typ der Hintergrundfüllung zurück. Lesen/Schreiben [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Gibt ein FillFormat für die Hintergrundfüllung BackgroundType.OwnBackground zurück. Nur lesend [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabewert:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Gibt ein EffectFormat für die Hintergrundfüllung BackgroundType.OwnBackground zurück. Nur lesend [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabewert:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Gibt ein ColorFormat für eine BackgroundType.Themed-Füllung zurück. Nur lesend [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabewert:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. 0 bedeutet keine Füllung. 1..999 – Index. Lesen/Schreiben int.

**Rückgabewert:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. 0 bedeutet keine Füllung. 1..999 – Index. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Liefert effektive Hintergrunddaten mit angewandter Vererbung.

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

**Rückgabewert:**  
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) – ein [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesend long.

**Rückgabewert:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesend IDOMObject.

**Rückgabewert:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Gibt die übergeordnete Folie einer Form zurück. Nur lesend [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabewert:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Gibt die übergeordnete Präsentation einer Folie zurück. Nur lesend [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**  
[Presentation](../../com.aspose.slides/presentation)