---
title: IFillOverlay
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa un efecto de superposición de relleno.
type: docs
url: /es/com.aspose.slides/ifilloverlay/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Representa un efecto de superposición de relleno. Una superposición de relleno puede usarse para especificar un relleno adicional para un objeto y combinar los dos rellenos juntos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Lectura/escritura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Devuelve:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Lectura/escritura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. Solo lectura [IFillFormat](../../com.aspose.slides/ifillformat).

**Devuelve:**
[IFillFormat](../../com.aspose.slides/ifillformat)