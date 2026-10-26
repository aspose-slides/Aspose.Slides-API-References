---
title: IBlurEffectiveData
second_title: Aspose.Slides voor Java API-referentie
description: Onveranderlijk object dat een Blur-effect vertegenwoordigt dat op de gehele vorm, inclusief de vulling, wordt toegepast.
type: docs
url: /nl/com.aspose.slides/iblureffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Onveranderlijk object dat een Blur-effect vertegenwoordigt dat op de hele vorm wordt toegepast, inclusief de vulling. Alle kleurkanalen, inclusief alfa, worden beïnvloed.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getRadius()](#getRadius--) | Geeft of stelt de blurstraal in. |
| [getGrow()](#getGrow--) | Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van het vervagen. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Geeft of stelt de blurstraal in. Alleen-lezen double.

**Retour:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Bepaalt of de grenzen van het object moeten worden vergroot als gevolg van het vervagen. True geeft aan dat de grenzen worden vergroot, terwijl false aangeeft dat dat niet het geval is. Alleen-lezen boolean.

**Retour:**
boolean