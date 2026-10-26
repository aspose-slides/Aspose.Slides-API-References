---
title: TextAnimation
second_title: Referencia de API de Aspose.Slides para Java
description: Representa la animación de texto.
type: docs
url: /es/com.aspose.slides/textanimation/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Representa animación de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Agregar un nuevo efecto al final de la secuencia actual al final de las animaciones de texto de grupo. |
| [getBuildType()](#getBuildType--) | Lista de tipo de compilación (por ejemplo |
| [setBuildType(int value)](#setBuildType-int-) | Lista de tipo de compilación (por ejemplo |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Efecto de forma vinculado con grupo o no (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Efecto de forma vinculado con grupo o no (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Agregar un nuevo efecto al final de la secuencia actual al final de las animaciones de texto de grupo. ¡Sólo válido si el recuento de párrafos de texto es igual o mayor que el recuento de efectos de este grupo!

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| effectType | int | Tipo de un efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de disparador del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Retorna:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Lista de tipo de compilación (p. ej. Párrafo 1,2,3, Todos a la vez) de la animación de texto. Lectura/escritura [BuildType](../../com.aspose.slides/buildtype).

**Devuelve:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Lista de tipo de compilación (p. ej. Párrafo 1,2,3, Todos a la vez) de la animación de texto. Lectura/escritura [BuildType](../../com.aspose.slides/buildtype).

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