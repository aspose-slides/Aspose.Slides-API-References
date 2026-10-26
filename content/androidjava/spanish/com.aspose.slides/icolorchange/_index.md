---
title: IColorChange
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un efecto de cambio de color.
type: docs
url: /es/com.aspose.slides/icolorchange/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Representa un efecto de cambio de color. Las instancias de FromColor se reemplazan con instancias de ToColor.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color que será reemplazado. |
| [getToColor()](#getToColor--) | Color que reemplazará. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

Color que será reemplazado. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

Color que reemplazará. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)