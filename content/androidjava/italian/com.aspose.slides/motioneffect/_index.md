---
title: MotionEffect
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta il comportamento dell'effetto di movimento.
type: docs
url: /it/com.aspose.slides/motioneffect/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Rappresenta il comportamento dell'effetto di movimento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |

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
| [getPath()](#getPath--) | Specifica il primitivo del percorso seguito dalle coordinate per il movimento dell'animazione. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Specifica il primitivo del percorso seguito dalle coordinate per il movimento dell'animazione. |
| [getPathEditMode()](#getPathEditMode--) | Specifica come il percorso di movimento si sposta quando la forma viene spostata. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Specifica come il percorso di movimento si sposta quando la forma viene spostata. |
| [getAngle()](#getAngle--) | Descrive l'angolo relativo del percorso di movimento. |
| [setAngle(float value)](#setAngle-float-) | Descrive l'angolo relativo del percorso di movimento. |

### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Specifica una coordinata x/y da cui avviare l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Specifica la posizione di destinazione per un effetto di movimento dell'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Descrive il valore di offset relativo per l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Descrive il valore di offset relativo per l'animazione (in percentuale). Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Descrive il centro di rotazione utilizzato per ruotare un percorso di movimento di un angolo X. Lettura/scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Descrive il centro di rotazione utilizzato per ruotare un percorso di movimento di un angolo X. Lettura/scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Specifica a cosa è relativa l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. Lettura/scrittura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Restituisce:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Specifica a cosa è relativa l'origine del percorso di movimento, ad esempio al layout della diapositiva o al genitore. Lettura/scrittura [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Specifica il primitivo del percorso seguito dalle coordinate per il movimento dell'animazione. Lettura/scrittura [IMotionPath](../../com.aspose.slides/imotionpath).

**Restituisce:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Specifica il primitivo del percorso seguito dalle coordinate per il movimento dell'animazione. Lettura/scrittura [IMotionPath](../../com.aspose.slides/imotionpath).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Specifica come il percorso di movimento si sposta quando la forma viene spostata. Lettura/scrittura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Restituisce:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Specifica come il percorso di movimento si sposta quando la forma viene spostata. Lettura/scrittura [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Descrive l'angolo relativo del percorso di movimento. Lettura/scrittura float.

**Restituisce:**
float

### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Descrive l'angolo relativo del percorso di movimento. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |