---
title: MotionEffect
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt het gedrag van een motion effect.
type: docs
url: /nl/com.aspose.slides/motioneffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**All Implemented Interfaces:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Vertegenwoordigt het gedrag van een motion effect.

## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFrom()](#getFrom--) | Specificeert een x/y-coördinaat om de animatie te starten (in procenten). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Specificeert een x/y-coördinaat om de animatie te starten (in procenten). |
| [getTo()](#getTo--) | Specificeert de doelpositie voor een motion-effect (in procenten). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Specificeert de doelpositie voor een motion-effect (in procenten). |
| [getBy()](#getBy--) | Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). |
| [getRotationCenter()](#getRotationCenter--) | Beschrijft het middelpunt van de rotatie die wordt gebruikt om een motion-pad te roteren met X-hoek. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Beschrijft het middelpunt van de rotatie die wordt gebruikt om een motion-pad te roteren met X-hoek. |
| [getOrigin()](#getOrigin--) | Specificeert wat de oorsprong van het motion-pad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende component. |
| [setOrigin(int value)](#setOrigin-int-) | Specificeert wat de oorsprong van het motion-pad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende component. |
| [getPath()](#getPath--) | Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-motion. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-motion. |
| [getPathEditMode()](#getPathEditMode--) | Specificeert hoe het motion-pad beweegt wanneer de vorm wordt verplaatst. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specificeert hoe het motion-pad beweegt wanneer de vorm wordt verplaatst. |
| [getAngle()](#getAngle--) | Beschrijft de relatieve hoek van het motion-pad. |
| [setAngle(float value)](#setAngle-float-) | Beschrijft de relatieve hoek van het motion-pad. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Specificeert een x/y-coördinaat om de animatie te starten (in procenten). Lezen/schrijven android.graphics.PointF.

**Retourwaarde:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Specificeert een x/y-coördinaat om de animatie te starten (in procenten). Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Specificeert de doelpositie voor een motion-effect (in procenten). Lezen/schrijven android.graphics.PointF.

**Retourwaarde:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Specificeert de doelpositie voor een motion-effect (in procenten). Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). Lezen/schrijven android.graphics.PointF.

**Retourwaarde:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Beschrijft het middelpunt van de rotatie die wordt gebruikt om een motion-pad te roteren met X-hoek. Lezen/schrijven android.graphics.PointF.

**Retourwaarde:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Beschrijft het middelpunt van de rotatie die wordt gebruikt om een motion-pad te roteren met X-hoek. Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Specificeert wat de oorsprong van het motion-pad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende component. Lezen/schrijven [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retourwaarde:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Specificeert wat de oorsprong van het motion-pad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende component. Lezen/schrijven [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-motion. Lezen/schrijven [IMotionPath](../../com.aspose.slides/imotionpath).

**Retourwaarde:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-motion. Lezen/schrijven [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Specificeert hoe het motion-pad beweegt wanneer de vorm wordt verplaatst. Lezen/schrijven [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Retourwaarde:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Specificeert hoe het motion-pad beweegt wanneer de vorm wordt verplaatst. Lezen/schrijven [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Beschrijft de relatieve hoek van het motion-pad. Lezen/schrijven float.

**Retourwaarde:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Beschrijft de relatieve hoek van het motion-pad. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |