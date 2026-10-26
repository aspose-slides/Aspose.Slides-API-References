---
title: IBlur
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een vervagingseffect voor dat wordt toegepast op de gehele vorm, inclusief de vulling.
type: docs
url: /nl/com.aspose.slides/iblur/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Stelt een vervagingseffect voor dat wordt toegepast op de gehele vorm, inclusief de vulling. Alle kleurkanalen, inclusief alfa, worden beïnvloed.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Retourneert of stelt de vervagingsradius in. |
| [setRadius(double value)](#setRadius-double-) | Retourneert of stelt de vervagingsradius in. |
| [getGrow()](#getGrow--) | Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Retourneert of stelt de vervagingsradius in. Lezen/schrijven double.

**Retour:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Retourneert of stelt de vervagingsradius in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. True geeft aan dat de grenzen worden vergroot terwijl false aangeeft dat dit niet het geval is. Lezen/schrijven boolean.

**Retour:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van de vervaging. True geeft aan dat de grenzen worden vergroot terwijl false aangeeft dat dit niet het geval is. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |