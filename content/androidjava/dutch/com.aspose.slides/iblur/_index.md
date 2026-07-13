---
title: IBlur
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een vervagingseffect voor dat wordt toegepast op de volledige vorm, inclusief de vulling.
type: docs
url: /nl/com.aspose.slides/iblur/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Stelt een vervagingseffect voor dat wordt toegepast op de volledige vorm, inclusief de vulling. Alle kleurkanalen, inclusief alfa, worden beïnvloed.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Geeft de vervagingsstraal terug of stelt deze in. |
| [setRadius(double value)](#setRadius-double-) | Geeft de vervagingsstraal terug of stelt deze in. |
| [getGrow()](#getGrow--) | Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Geeft de vervagingsstraal terug of stelt deze in. Lezen/Schrijven double.

**Retourwaarde:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Geeft de vervagingsstraal terug of stelt deze in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. True geeft aan dat de grenzen worden vergroot, terwijl false aangeeft dat dit niet het geval is. Lezen/Schrijven boolean.

**Retourwaarde:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. True geeft aan dat de grenzen worden vergroot, terwijl false aangeeft dat dit niet het geval is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |