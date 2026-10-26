---
title: IColorChange
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een kleuraanpassingseffect voor.
type: docs
url: /nl/com.aspose.slides/icolorchange/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Stelt een kleuraanpassingseffect voor. Instanties van FromColor worden vervangen door instanties van ToColor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFromColor()](#getFromColor--) | Kleur die vervangen zal worden. |
| [getToColor()](#getToColor--) | Kleur die zal vervangen. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

Kleur die vervangen zal worden. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

Kleur die zal vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retourneert:**
[IColorFormat](../../com.aspose.slides/icolorformat)