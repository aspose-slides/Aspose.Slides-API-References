---
title: IMotionEffect
second_title: Referência da API Aspose.Slides para Java
description: Representa o comportamento do efeito de movimento.
type: docs
url: /pt/com.aspose.slides/imotioneffect/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

Representa o comportamento do efeito de movimento do efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrom()](#getFrom--) | Especifica uma coordenada x/y para iniciar a animação (em porcentagem). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | Especifica uma coordenada x/y para iniciar a animação (em porcentagem). |
| [getTo()](#getTo--) | Especifica a localização alvo para um efeito de movimento de animação (em porcentagem). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | Especifica a localização alvo para um efeito de movimento de animação (em porcentagem). |
| [getBy()](#getBy--) | Descreve o valor de deslocamento relativo para a animação (em porcentagem). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | Descreve o valor de deslocamento relativo para a animação (em porcentagem). |
| [getRotationCenter()](#getRotationCenter--) | Descreve o centro de rotação usado para girar um caminho de movimento em ângulo X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | Descreve o centro de rotação usado para girar um caminho de movimento em ângulo X. |
| [getOrigin()](#getOrigin--) | Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o pai. |
| [setOrigin(int value)](#setOrigin-int-) | Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o pai. |
| [getPath()](#getPath--) | Especifica a primitiva de caminho seguida por coordenadas para o movimento da animação. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | Especifica a primitiva de caminho seguida por coordenadas para o movimento da animação. |
| [getPathEditMode()](#getPathEditMode--) | Especifica como o caminho de movimento se desloca quando a forma é movida. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | Especifica como o caminho de movimento se desloca quando a forma é movida. |
| [getAngle()](#getAngle--) | Descreve o ângulo relativo do caminho de movimento. |
| [setAngle(float value)](#setAngle-float-) | Descreve o ângulo relativo do caminho de movimento. |
### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```


Especifica uma coordenada x/y para iniciar a animação (em porcentagem). Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```


Especifica uma coordenada x/y para iniciar a animação (em porcentagem). Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```


Especifica a localização alvo para um efeito de movimento de animação (em porcentagem). Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```


Especifica a localização alvo para um efeito de movimento de animação (em porcentagem). Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```


Descreve o valor de deslocamento relativo para a animação (em porcentagem). Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```


Descreve o valor de deslocamento relativo para a animação (em porcentagem). Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```


Descreve o centro de rotação usado para girar um caminho de movimento em ângulo X. Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```


Descreve o centro de rotação usado para girar um caminho de movimento em ângulo X. Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```


Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o pai. Leitura/gravação [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Retorna:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```


Especifica qual é a origem do caminho de movimento em relação a, por exemplo, o layout do slide ou o pai. Leitura/gravação [MotionOriginType](../../com.aspose.slides/motionorigintype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```


Especifica a primitiva de caminho seguida por coordenadas para o movimento da animação. Leitura/gravação [IMotionPath](../../com.aspose.slides/imotionpath).

**Retorna:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```


Especifica a primitiva de caminho seguida por coordenadas para o movimento da animação. Leitura/gravação [IMotionPath](../../com.aspose.slides/imotionpath).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```


Especifica como o caminho de movimento se desloca quando a forma é movida. Leitura/gravação [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**Retorna:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```


Especifica como o caminho de movimento se desloca quando a forma é movida. Leitura/gravação [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

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