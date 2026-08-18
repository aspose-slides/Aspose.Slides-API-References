---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Representar animación de texto.
type: docs
url: /es/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Representar animación de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Agregar un nuevo efecto al final de la secuencia actual al final de las animaciones de texto en grupo. |
| [getBuildType()](#getBuildType--) | Lista de tipos de compilación (para exp. |
| [setBuildType(int value)](#setBuildType-int-) | Lista de tipos de compilación (para exp. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Efecto de forma enlazada con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Efecto de forma enlazada con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Agregar un nuevo efecto al final de la secuencia actual al final de las animaciones de texto en grupo. ¡Solo válido si el recuento de párrafos de texto es igual o mayor que el recuento de efectos de este grupo!

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de activación del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Lista de tipos de compilación (por ejemplo, Párrafo 1,2,3, Todos a la vez) de la animación de texto. Lectura/escritura \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Devuelve:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Lista de tipos de compilación (por ejemplo, Párrafo 1,2,3, Todos a la vez) de la animación de texto. Lectura/escritura \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Efecto de forma enlazada con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect).

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Efecto de forma enlazada con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |