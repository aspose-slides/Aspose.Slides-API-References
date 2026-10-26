---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /fr/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Représente le gestionnaire d'enregistrement d'image Markdown de l'événement \#ImageSavingDelegate.ImageSavingDelegate.
## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoked for each non-SVG image (bitmap or metafile) during Markdown export. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```


Appelé pour chaque image non SVG (bitmap ou métafile) lors de l'exportation Markdown. Retournez true pour utiliser le lien spécifié, ou false pour appliquer la logique d'enregistrement par défaut.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | L'image en cours d'exportation (bitmap ou métafile). |
| format | int | Le format de l'image. |
| link | java.lang.String[] | Le lien Markdown à utiliser lorsqu'on retourne true. |

**Valeur de retour :**
boolean