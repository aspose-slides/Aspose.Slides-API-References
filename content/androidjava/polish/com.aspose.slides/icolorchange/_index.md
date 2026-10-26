---
title: IColorChange
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje efekt zmiany koloru.
type: docs
url: /pl/com.aspose.slides/icolorchange/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Reprezentuje efekt zmiany koloru. Instancje FromColor są zastępowane instancjami ToColor.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFromColor()](#getFromColor--) | Kolor, który zostanie zastąpiony. |
| [getToColor()](#getToColor--) | Kolor, który zastąpi. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Kolor, który zostanie zastąpiony. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Kolor, który zastąpi. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)