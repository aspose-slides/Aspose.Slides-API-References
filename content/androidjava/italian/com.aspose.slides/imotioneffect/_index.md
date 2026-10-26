---
title: IMotionEffect
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il comportamento dell'effetto di movimento.
type: docs
url: /it/com.aspose.slides/imotioneffect/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Rappresenta il comportamento dell'effetto di movimento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFrom()](#getFrom--) | Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). |
| [getTo()](#getTo--) | Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). |
| [getBy()](#getBy--) | Descrive il valore di offset relativo per l'animazione (in percentuale). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Descrive il valore di offset relativo per l'animazione (in percentuale). |
| [getRotationCenter()](#getRotationCenter--) | Descrive il centro di rotazione utilizzato per ruotare un percorso di movimento di un angolo X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Descrive il centro di rotazione utilizzato per ruotare un percorso di movimento di un angolo X. |
| [getOrigin()](#getOrigin--) | Specifica a cosa è relativa l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. |
| [setOrigin(int value)](#setOrigin-int-) | Specifica a cosa è relativa l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. |
| [getPath()](#getPath--) | Specifica il primitivo del percorso seguito da coordinate per il movimento dell'animazione. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specifica il primitivo del percorso seguito da coordinate per il movimento dell'animazione. |
| [getPathEditMode()](#getPathEditMode--) | Specifica come il percorso di movimento si muove quando la forma viene spostata. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specifica come il percorso di movimento si muove quando la forma viene spostata. |
| [getAngle()](#getAngle--) | Descrive l'angolo relativo del percorso di movimento. |
| [setAngle(float value)](#setAngle-float-) | Descrive l'angolo relativo del percorso di movimento. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Descrive il valore di offset relativo per l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Descrive il valore di offset relativo per l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Descrive il centro di rotazione utilizzato per ruotare un percorso di movimento di un angolo X. Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Descrive il centro di rotazione utilizzato per ruotare un percorso di movimento di un angolo X. Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Specifica a cosa è relativa l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. Lettura/scrittura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Restituisce:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Specifica a cosa è relativa l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. Lettura/scrittura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Specifica il primitivo del percorso seguito da coordinate per il movimento dell'animazione. Lettura/scrittura [IMotionPath](../../com.aspose.slides/imotionpath).

**Restituisce:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Specifica il primitivo del percorso seguito da coordinate per il movimento dell'animazione. Lettura/scrittura [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Specifica come il percorso di movimento si muove quando la forma viene spostata. Lettura/scrittura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Restituisce:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Specifica come il percorso di movimento si muove quando la forma viene spostata. Lettura/scrittura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

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