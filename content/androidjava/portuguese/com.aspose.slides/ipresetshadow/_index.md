---
title: IPresetShadow
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um efeito de sombra predefinido.
type: docs
url: /pt/com.aspose.slides/ippresetshadow/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IPresetShadow extends IImageTransformOperation, IAccessiblePVIObject<IPresetShadowEffectiveData>
```

Representa um efeito de sombra predefinido.
## Métodos

| Método | Descrição |
| --- | --- |
| [getDirection()](#getDirection--) | Direção da sombra. |
| [setDirection(float value)](#setDirection-float-) | Direção da sombra. |
| [getDistance()](#getDistance--) | Distância da sombra. |
| [setDistance(double value)](#setDistance-double-) | Distância da sombra. |
| [getShadowColor()](#getShadowColor--) | Cor da sombra. |
| [getPreset()](#getPreset--) | Predefinição. |
| [setPreset(int value)](#setPreset-int-) | Predefinição. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Direção da sombra. Leitura/gravação float.

**Retorna:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Direção da sombra. Leitura/gravação float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Distância da sombra. Leitura/gravação double.

**Retorna:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Distância da sombra. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Cor da sombra. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```


Predefinição. Leitura/gravação [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Retorna:**
int
### setPreset(int value) {#setPreset-int-}
```
public abstract void setPreset(int value)
```


Predefinição. Leitura/gravação [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |