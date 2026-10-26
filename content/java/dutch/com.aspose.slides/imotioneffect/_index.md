---
title: IMotionEffect
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt het gedrag van een bewegings-effect.
type: docs
url: /nl/com.aspose.slides/imotioneffect/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Vertegenwoordigt het gedrag van een bewegings-effect.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFrom()](#getFrom--) | Specificeert een x/y-coördinaat om de animatie te starten (in procenten). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Specificeert een x/y-coördinaat om de animatie te starten (in procenten). |
| [getTo()](#getTo--) | Specificeert de doellocatie voor een bewegings-effect (in procenten). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Specificeert de doellocatie voor een bewegings-effect (in procenten). |
| [getBy()](#getBy--) | Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). |
| [getRotationCenter()](#getRotationCenter--) | Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X hoek te draaien. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X hoek te draaien. |
| [getOrigin()](#getOrigin--) | Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende. |
| [setOrigin(int value)](#setOrigin-int-) | Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende. |
| [getPath()](#getPath--) | Specificeert de padprimitive gevolgd door coördinaten voor de animatiebeweging. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specificeert de padprimitive gevolgd door coördinaten voor de animatiebeweging. |
| [getPathEditMode()](#getPathEditMode--) | Specificeert hoe het bewegingspad beweegt wanneer de vorm wordt verplaatst. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specificeert hoe het bewegingspad beweegt wanneer de vorm wordt verplaatst. |
| [getAngle()](#getAngle--) | Beschrijft de relatieve hoek van het bewegingspad. |
| [setAngle(float value)](#setAngle-float-) | Beschrijft de relatieve hoek van het bewegingspad. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Specificeert een x/y-coördinaat om de animatie te starten (in procenten). Lezen/schrijven java.awt.geom.Point2D.Float.

**Retour:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Specificeert een x/y-coördinaat om de animatie te starten (in procenten). Lezen/schrijven java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Specificeert de doellocatie voor een bewegings-effect (in procenten). Lezen/schrijven java.awt.geom.Point2D.Float.

**Retour:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Specificeert de doellocatie voor een bewegings-effect (in procenten). Lezen/schrijven java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). Lezen/schrijven java.awt.geom.Point2D.Float.

**Retour:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). Lezen/schrijven java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X hoek te draaien. Lezen/schrijven java.awt.geom.Point2D.Float.

**Retour:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X hoek te draaien. Lezen/schrijven java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende. Lezen/schrijven [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retour:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggende. Lezen/schrijven [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Specificeert de padprimitive gevolgd door coördinaten voor de animatiebeweging. Lezen/schrijven [IMotionPath](../../com.aspose.slides/imotionpath).

**Retour:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Specificeert de padprimitive gevolgd door coördinaten voor de animatiebeweging. Lezen/schrijven [IMotionPath](../../com.aspose.slides/imotionpath).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Specificeert hoe het bewegingspad beweegt wanneer de vorm wordt verplaatst. Lezen/schrijven [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Retour:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Specificeert hoe het bewegingspad beweegt wanneer de vorm wordt verplaatst. Lezen/schrijven [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Beschrijft de relatieve hoek van het bewegingspad. Lezen/schrijven float.

**Retour:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Beschrijft de relatieve hoek van het bewegingspad. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |