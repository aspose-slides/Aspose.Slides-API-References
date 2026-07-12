---
title: TextAnimation
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa animación de texto.
type: docs
url: /es/com.aspose.slides/textanimation/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Representa la animación de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Add new effect to the end of current sequence to end of group text animations. |
| [getBuildType()](#getBuildType--) | List of build type (for exp. |
| [setBuildType(int value)](#setBuildType-int-) | List of build type (for exp. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Linked shape effect with group or not (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Linked shape effect with group or not (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Agregar un nuevo efecto al final de la secuencia actual hasta el final de las animaciones de texto del grupo. ¡Solo válido si el recuento de párrafos de texto es igual o mayor que la cantidad de efectos de este grupo!

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| effectType | int | Type of an animation effect [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtypes of animation effect [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Trigger type of effect [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - New effect object [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Lista del tipo de construcción (por ejemplo Paragraph 1,2,3, Todo a la vez) de la animación de texto. Lectura/escritura [BuildType](../../com.aspose.slides/buildtype).

**Devuelve:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Lista del tipo de construcción (por ejemplo Paragraph 1,2,3, Todo a la vez) de la animación de texto. Lectura/escritura [BuildType](../../com.aspose.slides/buildtype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Efecto de forma vinculado con grupo o no (null). Lectura/escritura [IEffect](../../com.aspose.slides/ieffect).

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Efecto de forma vinculado con grupo o no (null). Lectura/escritura [IEffect](../../com.aspose.slides/ieffect).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |