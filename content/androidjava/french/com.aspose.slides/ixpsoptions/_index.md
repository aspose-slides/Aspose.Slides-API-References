---
title: IXpsOptions
second_title: Aspose.Slides pour Android via la référence API Java
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
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True pour dessiner un cadre noir autour de chaque diapositive. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True pour dessiner un cadre noir autour de chaque diapositive. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Indique si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Indique si le document généré doit inclure les diapositives masquées ou non. |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Booléen lecture/écriture.

--------------------

La valeur par défaut est **true**.

**Renvoie :**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Booléen lecture/écriture.

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

True pour dessiner un cadre noir autour de chaque diapositive. Booléen lecture/écriture.

--------------------

La valeur par défaut est **false**.

**Renvoie :**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True pour dessiner un cadre noir autour de chaque diapositive. Booléen lecture/écriture.

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

Indique si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Renvoie :**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Indique si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |