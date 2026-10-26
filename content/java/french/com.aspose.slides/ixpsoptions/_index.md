---
title: IXpsOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format XPS.
type: docs
url: /fr/com.aspose.slides/ixpsoptions/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format XPS.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Vrai pour dessiner un cadre noir autour de chaque diapositive. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Vrai pour dessiner un cadre noir autour de chaque diapositive. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Indique si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Indique si le document généré doit inclure les diapositives masquées ou non. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean.

--------------------

La valeur par défaut est **true**.

**Retour :**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


Vrai pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Lecture/écriture boolean.

--------------------

La valeur par défaut est **true**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```


Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture boolean.

--------------------

La valeur par défaut est **false**.

**Retour :**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


Vrai pour dessiner un cadre noir autour de chaque diapositive. Lecture/écriture boolean.

--------------------

La valeur par défaut est **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Indique si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est **false**.

**Retour :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Indique si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |