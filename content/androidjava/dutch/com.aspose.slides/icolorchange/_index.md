---
title: IColorChange
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een kleurveranderingseffect voor.
type: docs
url: /nl/com.aspose.slides/icolorchange/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Stelt een kleurveranderingseffect voor. Instanties van FromColor worden vervangen door instanties van ToColor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFromColor()](#getFromColor--) | Kleur die wordt vervangen. |
| [getToColor()](#getToColor--) | Kleur die vervangt. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

Kleur die wordt vervangen. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

Kleur die vervangt. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**
[IColorFormat](../../com.aspose.slides/icolorformat)