---
title: MotionEffect
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o comportamento do efeito de movimento.
type: docs
url: /pt/com.aspose.slides/motioneffect/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)
```
public class MotionEffect extends Behavior implements IMotionEffect
```

Representa o comportamento de efeito de movimento do efeito.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica uma coordenada x/y para iniciar a animação (em percentuais). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | Especifica uma coordenada x/y para iniciar a animação (em percentuais). |
| [getTo()](#getTo--) | Especifica a localização de destino para um efeito de movimento de animação (em percentuais). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | Especifica a localização de destino para um efeito de movimento de animação (em percentuais). |
| [getBy()](#getBy--) | Descreve o valor de deslocamento relativo para a animação (em percentuais). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | Descreve o valor de deslocamento relativo para a animação (em percentuais). |
| [getRotationCenter()](#getRotationCenter--) | Descreve o centro da rotação usado para girar um caminho de movimento em um ângulo X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | Descreve o centro da rotação usado para girar um caminho de movimento em um ângulo X. |
| [getOrigin()](#getOrigin--) | Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o elemento pai. |
| [setOrigin(int value)](#setOrigin-int-) | Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o elemento pai. |
| [getPath()](#getPath--) | Especifica o caminho primitivo seguido por coordenadas para o movimento da animação. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Especifica o caminho primitivo seguido por coordenadas para o movimento da animação. |
| [getPathEditMode()](#getPathEditMode--) | Especifica como o caminho de movimento se desloca quando a forma é movida. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Especifica como o caminho de movimento se desloca quando a forma é movida. |
| [getAngle()](#getAngle--) | Descreve o ângulo relativo do caminho de movimento. |
| [setAngle(float value)](#setAngle-float-) | Descreve o ângulo relativo do caminho de movimento. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

Especifica uma coordenada x/y para iniciar a animação (em percentuais). Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

Especifica uma coordenada x/y para iniciar a animação (em percentuais). Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

Especifica a localização de destino para um efeito de movimento de animação (em percentuais). Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

Especifica a localização de destino para um efeito de movimento de animação (em percentuais). Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

Descreve o valor de deslocamento relativo para a animação (em percentuais). Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

Descreve o valor de deslocamento relativo para a animação (em percentuais). Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

Descreve o centro da rotação usado para girar um caminho de movimento em um ângulo X. Leitura/gravação android.graphics.PointF.

**Retorna:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

Descreve o centro da rotação usado para girar um caminho de movimento em um ângulo X. Leitura/gravação android.graphics.PointF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o elemento pai. Leitura/gravação [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retorna:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o elemento pai. Leitura/gravação [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

Especifica o caminho primitivo seguido por coordenadas para o movimento da animação. Leitura/gravação [IMotionPath](../../com.aspose.slides/imotionpath).

**Retorna:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

Especifica o caminho primitivo seguido por coordenadas para o movimento da animação. Leitura/gravação [IMotionPath](../../com.aspose.slides/imotionpath).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

Especifica como o caminho de movimento se desloca quando a forma é movida. Leitura/gravação [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Retorna:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

Especifica como o caminho de movimento se desloca quando a forma é movida. Leitura/gravação [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

Descreve o ângulo relativo do caminho de movimento. Leitura/gravação float.

**Retorna:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

Descreve o ângulo relativo do caminho de movimento. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |