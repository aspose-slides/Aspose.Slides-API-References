---
title: IMotionEffect
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o comportamento do efeito de movimento.
type: docs
url: /pt/com.aspose.slides/imotioneffect/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Representa o comportamento do efeito de movimento.

## Métodos

| Método | Descrição |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica uma coordenada x/y para iniciar a animação (em porcentagens). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Especifica uma coordenada x/y para iniciar a animação (em porcentagens). |
| [getTo()](#getTo--) | Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). |
| [getBy()](#getBy--) | Descreve o valor de deslocamento relativo para a animação (em porcentagens). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Descreve o valor de deslocamento relativo para a animação (em porcentagens). |
| [getRotationCenter()](#getRotationCenter--) | Descreve o centro da rotação usado para girar um caminho de movimento em ângulo X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Descreve o centro da rotação usado para girar um caminho de movimento em ângulo X. |
| [getOrigin()](#getOrigin--) | Especifica qual é a origem do caminho de movimento em relação a algo, como o layout do slide ou o pai. |
| [setOrigin(int value)](#setOrigin-int-) | Especifica qual é a origem do caminho de movimento em relação a algo, como o layout do slide ou o pai. |
| [getPath()](#getPath--) | Especifica a primitiva de caminho seguida por coordenadas para a animação de movimento. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Especifica a primitiva de caminho seguida por coordenadas para a animação de movimento. |
| [getPathEditMode()](#getPathEditMode--) | Especifica como o caminho de movimento se move quando a forma é movida. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Especifica como o caminho de movimento se move quando a forma é movida. |
| [getAngle()](#getAngle--) | Descreve o ângulo relativo do caminho de movimento. |
| [setAngle(float value)](#setAngle-float-) | Descreve o ângulo relativo do caminho de movimento. |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

Especifica uma coordenada x/y para iniciar a animação (em porcentagens). Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

Especifica uma coordenada x/y para iniciar a animação (em porcentagens). Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

Descreve o valor de deslocamento relativo para a animação (em porcentagens). Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

Descreve o valor de deslocamento relativo para a animação (em porcentagens). Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```

Descreve o centro da rotação usado para girar um caminho de movimento em ângulo X. Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF

### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```

Descreve o centro da rotação usado para girar um caminho de movimento em ângulo X. Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

Especifica qual é a origem do caminho de movimento em relação a algo, como o layout do slide ou o pai. Leitura/gravação [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retorna:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

Especifica qual é a origem do caminho de movimento em relação a algo, como o layout do slide ou o pai. Leitura/gravação [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

Especifica a primitiva de caminho seguida por coordenadas para a animação de movimento. Leitura/gravação [IMotionPath](../../com.aspose.slides/imotionpath).

**Retorna:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

Especifica a primitiva de caminho seguida por coordenadas para a animação de movimento. Leitura/gravação [IMotionPath](../../com.aspose.slides/imotionpath).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

Especifica como o caminho de movimento se move quando a forma é movida. Leitura/gravação [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Retorna:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

Especifica como o caminho de movimento se move quando a forma é movida. Leitura/gravação [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

Descreve o ângulo relativo do caminho de movimento. Leitura/gravação float.

**Retorna:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

Descreve o ângulo relativo do caminho de movimento. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |