---
title: IColorChange
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Představuje efekt změny barvy.
type: docs
url: /cs/com.aspose.slides/icolorchange/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Představuje efekt změny barvy. Instance FromColor jsou nahrazeny instancemi ToColor.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFromColor()](#getFromColor--) | Barva, která bude nahrazena. |
| [getToColor()](#getToColor--) | Barva, která nahradí. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Barva, která bude nahrazena. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Barva, která nahradí. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)