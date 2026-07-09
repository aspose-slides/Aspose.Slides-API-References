---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Représente le gestionnaire d'enregistrement d'image SVG markdown de l'événement SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /fr/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Représente le gestionnaire d'enregistrement d'image SVG markdown de l'événement \#SvgImageSavingDelegate.SvgImageSavingDelegate.

## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Appelé pour chaque image SVG lors de l'exportation Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Appelé pour chaque image SVG lors de l'exportation Markdown. Retournez true pour utiliser le lien spécifié, ou false pour appliquer la logique d'enregistrement par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | L'image SVG en cours d'exportation. |
| link | java.lang.String[] | Le lien Markdown à utiliser lorsque la fonction retourne true. |

**Valeur de retour :**
boolean