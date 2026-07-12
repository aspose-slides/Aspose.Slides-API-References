---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: Represent text animation.
type: docs
url: /es/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Representar animación de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Agregar nuevo efecto al final de la secuencia actual al final de las animaciones de texto del grupo. |
| [getBuildType()](#getBuildType--) | Lista de tipo de construcción (por ejemplo |
| [setBuildType(int value)](#setBuildType-int-) | Lista de tipo de construcción (por ejemplo |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Efecto de forma enlazado con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Efecto de forma enlazado con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect). |

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Agregar nuevo efecto al final de la secuencia actual al final de las animaciones de texto del grupo. ¡Solo válido si la cantidad de párrafos de texto es igual o mayor que la cantidad de efectos de este grupo!

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de disparador del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Lista de tipo de construcción (por ejemplo Párrafo 1,2,3, Todo a la vez) de la animación de texto. Lectura/escritura \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Devuelve:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Lista de tipo de construcción (por ejemplo Párrafo 1,2,3, Todo a la vez) de la animación de texto. Lectura/escritura \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


Efecto de forma enlazado con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect).

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


Efecto de forma enlazado con grupo o no (null) Lectura/escritura [IEffect](../../com.aspose.slides/ieffect).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |