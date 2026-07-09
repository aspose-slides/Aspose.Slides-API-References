---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Représente le gestionnaire d’enregistrement d’image markdown de l’événement ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /fr/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Représente le gestionnaire d’enregistrement d’image markdown de l’événement #ImageSavingDelegate.ImageSavingDelegate.

## Méthodes

| Méthode | Description |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invoqué pour chaque image non-SVG (bitmap ou métafichier) lors de l’exportation Markdown. |

### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Invoqué pour chaque image non-SVG (bitmap ou métafichier) lors de l’exportation Markdown. Retournez true pour utiliser le lien spécifié, ou false pour appliquer la logique d’enregistrement par défaut.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | L’image en cours d’exportation (bitmap ou métafichier). |
| format | int | Le format de l’image. |
| link | java.lang.String[] | Le lien Markdown à utiliser lorsqu’on retourne true. |

**Renvoie :**
boolean