---
title: IMotionEffect
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta il comportamento dell'effetto di movimento.
type: docs
url: /it/com.aspose.slides/imotioneffect/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Rappresenta il comportamento dell'effetto di movimento di un effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFrom()](#getFrom--) | Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). |
| [getTo()](#getTo--) | Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). |
| [getBy()](#getBy--) | Descrive il valore di offset relativo per l'animazione (in percentuale). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Descrive il valore di offset relativo per l'animazione (in percentuale). |
| [getRotationCenter()](#getRotationCenter--) | Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X. |
| [getOrigin()](#getOrigin--) | Specifica l'origine del percorso di movimento rispetto a, ad esempio, il layout della diapositiva o il genitore. |
| [setOrigin(int value)](#setOrigin-int-) | Specifica l'origine del percorso di movimento rispetto a, ad esempio, il layout della diapositiva o il genitore. |
| [getPath()](#getPath--) | Specifica il primitivo di percorso seguito da coordinate per il movimento dell'animazione. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specifica il primitivo di percorso seguito da coordinate per il movimento dell'animazione. |
| [getPathEditMode()](#getPathEditMode--) | Specifica come si muove il percorso di movimento quando la forma viene spostata. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specifica come si muove il percorso di movimento quando la forma viene spostata. |
| [getAngle()](#getAngle--) | Descrive l'angolo relativo del percorso di movimento. |
| [setAngle(float value)](#setAngle-float-) | Descrive l'angolo relativo del percorso di movimento. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). Lettura/scrittura java.awt.geom.Point2D.Float.

**Restituisce:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). Lettura/scrittura java.awt.geom.Point2D.Float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). Lettura/scrittura java.awt.geom.Point2D.Float.

**Restituisce:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). Lettura/scrittura java.awt.geom.Point2D.Float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

Descrive il valore di offset relativo per l'animazione (in percentuale). Lettura/scrittura java.awt.geom.Point2D.Float.

**Restituisce:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

Descrive il valore di offset relativo per l'animazione (in percentuale). Lettura/scrittura java.awt.geom.Point2D.Float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X. Lettura/scrittura java.awt.geom.Point2D.Float.

**Restituisce:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

Descrive il centro di rotazione usato per ruotare un percorso di movimento di un angolo X. Lettura/scrittura java.awt.geom.Point2D.Float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Specifica l'origine del percorso di movimento rispetto a, ad esempio, il layout della diapositiva o il genitore. Lettura/scrittura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Restituisce:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Specifica l'origine del percorso di movimento rispetto a, ad esempio, il layout della diapositiva o il genitore. Lettura/scrittura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Specifica il primitivo di percorso seguito da coordinate per il movimento dell'animazione. Lettura/scrittura [IMotionPath](../../com.aspose.slides/imotionpath).

**Restituisce:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Specifica il primitivo di percorso seguito da coordinate per il movimento dell'animazione. Lettura/scrittura [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Specifica come si muove il percorso di movimento quando la forma viene spostata. Lettura/scrittura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Restituisce:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Specifica come si muove il percorso di movimento quando la forma viene spostata. Lettura/scrittura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Descrive l'angolo relativo del percorso di movimento. Lettura/scrittura float.

**Restituisce:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Descrive l'angolo relativo del percorso di movimento. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |