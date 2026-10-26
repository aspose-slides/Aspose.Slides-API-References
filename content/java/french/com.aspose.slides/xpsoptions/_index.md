---
title: XpsOptions
second_title: Référence API Aspose.Slides pour Java
description: Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format XPS.
type: docs
url: /fr/com.aspose.slides/xpsoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Enregistre la présentation dans un document XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Instancie la classe TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Enregistre les métafichiers en PNG
>      options.setSaveMetafilesAsPng(true);
>      // Enregistre la présentation dans un document XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Constructeur par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True pour dessiner un cadre noir autour de chaque diapositive. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True pour dessiner un cadre noir autour de chaque diapositive. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Constructeur par défaut.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est **false**.

**Renvoie :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Booléen en lecture/écriture.

--------------------

Par défaut, **true**.

**Renvoie :**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True pour convertir tous les métafichiers utilisés dans une présentation en images PNG. Booléen en lecture/écriture.

--------------------

Par défaut, **true**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True pour dessiner un cadre noir autour de chaque diapositive. Booléen en lecture/écriture.

--------------------

Par défaut, **false**.

**Renvoie :**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True pour dessiner un cadre noir autour de chaque diapositive. Booléen en lecture/écriture.

--------------------

Par défaut, **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |