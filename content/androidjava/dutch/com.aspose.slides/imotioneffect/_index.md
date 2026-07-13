---
title: IMotionEffect
second_title: Aspose.Slides voor Android via Java API-referentie
description: Geeft het gedrag van een bewegings-effect weer.
type: docs
url: /nl/com.aspose.slides/imotioneffect/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Geeft het gedrag van een bewegings-effect weer.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFrom()](#getFrom--) | Specificeert een x/y-coördinaat om de animatie vanaf te starten (in procenten). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Specificeert een x/y-coördinaat om de animatie vanaf te starten (in procenten). |
| [getTo()](#getTo--) | Specificeert de doel-locatie voor een animatie-bewegings-effect (in procenten). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Specificeert de doel-locatie voor een animatie-bewegings-effect (in procenten). |
| [getBy()](#getBy--) | Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). |
| [getRotationCenter()](#getRotationCenter--) | Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X-hoek te roteren. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X-hoek te roteren. |
| [getOrigin()](#getOrigin--) | Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggend element. |
| [setOrigin(int value)](#setOrigin-int-) | Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggend element. |
| [getPath()](#getPath--) | Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-beweging. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-beweging. |
| [getPathEditMode()](#getPathEditMode--) | Specificeert hoe het bewegingspad beweegt wanneer de vorm wordt verplaatst. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specificeert hoe het bewegingspad beweegt wanneer de vorm wordt verplaatst. |
| [getAngle()](#getAngle--) | Beschrijft de relatieve hoek van het bewegingspad. |
| [setAngle(float value)](#setAngle-float-) | Beschrijft de relatieve hoek van het bewegingspad. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```


Specificeert een x/y-coördinaat om de animatie vanaf te starten (in procenten). Lezen/schrijven android.graphics.PointF.

**Retour:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```


Specificeert een x/y-coördinaat om de animatie vanaf te starten (in procenten). Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```


Specificeert de doel-locatie voor een animatie-bewegings-effect (in procenten). Lezen/schrijven android.graphics.PointF.

**Retour:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```


Specificeert de doel-locatie voor een animatie-bewegings-effect (in procenten). Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```


Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). Lezen/schrijven android.graphics.PointF.

**Retour:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```


Beschrijft de relatieve offsetwaarde voor de animatie (in procenten). Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```


Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X-hoek te roteren. Lezen/schrijven android.graphics.PointF.

**Retour:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```


Beschrijft het draaipunt dat wordt gebruikt om een bewegingspad met X-hoek te roteren. Lezen/schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```


Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggend element. Lezen/schrijven [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retour:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```


Specificeert wat de oorsprong van het bewegingspad is ten opzichte van bijvoorbeeld de lay-out van de dia of de bovenliggend element. Lezen/schrijven [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```


Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-beweging. Lezen/schrijven [IMotionPath](../../com.aspose.slides/imotionpath).

**Retour:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```


Specificeert de pad-primitive gevolgd door coördinaten voor de animatie-beweging. Lezen/schrijven [IMotionPath](../../com.aspose.slides/imotionpath).

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