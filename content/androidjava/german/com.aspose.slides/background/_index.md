---
title: Background
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getFillFormat()](#getFillFormat--) | Gibt ein FillFormat für die BackgroundType.OwnBackground-Füllung zurück. |
| [getEffectFormat()](#getEffectFormat--) | Gibt ein EffectFormat für die BackgroundType.OwnBackground-Füllung zurück. |
| [getStyleColor()](#getStyleColor--) | Gibt ein ColorFormat für eine BackgroundType.Themed-Füllung zurück. |
| [getStyleIndex()](#getStyleIndex--) | Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. |
| [getEffective()](#getEffective--) | Ruft effektive Hintergrunddaten mit angewandter Vererbung ab. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie einer Form zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation einer Folie zurück. |

### getType() {#getType--}
```
public final byte getType()
```

Gibt einen Typ der Hintergrundfüllung zurück. Lese/Schreiben [BackgroundType](../../com.aspose.slides/backgroundtype).

**Rückgabe:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Gibt einen Typ der Hintergrundfüllung zurück. Lese/Schreiben [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Gibt ein FillFormat für die BackgroundType.OwnBackground-Füllung zurück. Nur-Lesen [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

Gibt ein EffectFormat für die BackgroundType.OwnBackground-Füllung zurück. Nur-Lesen [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Rückgabe:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

Gibt ein ColorFormat für eine BackgroundType.Themed-Füllung zurück. Nur-Lesen [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. 0 bedeutet keine Füllung. 1..999 – Index. Lese/Schreiben int.

**Rückgabe:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

Gibt den Index einer BackgroundType.Themed-Füllung in der Hintergrund-Themensammlung zurück. 0 bedeutet keine Füllung. 1..999 – Index. Lese/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Ruft effektive Hintergrunddaten mit angewandter Vererbung ab.

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

**Rückgabe:**  
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) – ein [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lesen long.

**Rückgabe:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt ein Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabe:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Gibt die übergeordnete Folie einer Form zurück. Nur-Lesen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Gibt die übergeordnete Präsentation einer Folie zurück. Nur-Lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**  
[Presentation](../../com.aspose.slides/presentation)