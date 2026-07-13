---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta il gestore di salvataggio delle immagini markdown dell'evento ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /it/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Rappresenta il gestore di salvataggio delle immagini markdown dell'evento \#ImageSavingDelegate.ImageSavingDelegate.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invocata per ciascuna immagine non SVG (bitmap o metafile) durante l'esportazione Markdown. |

### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Invocata per ciascuna immagine non SVG (bitmap o metafile) durante l'esportazione Markdown. Restituisce true per utilizzare il link specificato, o false per applicare la logica di salvataggio predefinita.

**Parametri:**
| Parametro | Type | Descrizione |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | L'immagine esportata (bitmap o metafile). |
| format | int | Il formato dell'immagine. |
| link | java.lang.String[] | Il link Markdown da utilizzare quando si restituisce true. |

**Restituisce:**
boolean