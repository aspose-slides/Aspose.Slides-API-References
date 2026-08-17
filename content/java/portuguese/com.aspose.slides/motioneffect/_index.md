---
title: MotionEffect
second_title: Referência da API Aspose.Slides para Java
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

Representa o comportamento do efeito de movimento do efeito.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica uma coordenada x/y para iniciar a animação (em porcentagens). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Especifica uma coordenada x/y para iniciar a animação (em porcentagens). |
| [getTo()](#getTo--) | Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). |
| [getBy()](#getBy--) | Descreve o valor de deslocamento relativo da animação (em porcentagens). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Descreve o valor de deslocamento relativo da animação (em porcentagens). |
| [getRotationCenter()](#getRotationCenter--) | Descreve o centro da rotação usado para girar um caminho de movimento por ângulo X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Descreve o centro da rotação usado para girar um caminho de movimento por ângulo X. |
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
public final Point2D.Float getFrom()
```

Especifica uma coordenada x/y para iniciar a animação (em porcentagens). Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```

Especifica uma coordenada x/y para iniciar a animação (em porcentagens). Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```

Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```

Especifica a localização de destino para um efeito de movimento de animação (em porcentagens). Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```

Descreve o valor de deslocamento relativo da animação (em porcentagens). Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```

Descreve o valor de deslocamento relativo da animação (em porcentagens). Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```

Descreve o centro da rotação usado para girar um caminho de movimento por ângulo X. Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```

Descreve o centro da rotação usado para girar um caminho de movimento por ângulo X. Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

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