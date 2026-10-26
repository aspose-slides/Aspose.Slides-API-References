---
title: IColorChange
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en färgändringseffekt.
type: docs
url: /sv/com.aspose.slides/icolorchange/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Representerar en färgändringseffekt. Instanser av FromColor ersätts med instanser av ToColor.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFromColor()](#getFromColor--) | Färg som kommer att ersättas. |
| [getToColor()](#getToColor--) | Färg som kommer att ersätta. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Färg som kommer att ersättas. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Färg som kommer att ersätta. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)