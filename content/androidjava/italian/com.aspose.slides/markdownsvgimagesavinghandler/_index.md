---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta il gestore del salvataggio dell'immagine SVG markdown dell'evento SvgImageSavingDelegate.SvgImageSavingDelegate.
type: docs
url: /it/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Rappresenta il gestore del salvataggio dell'immagine SVG markdown dell'evento \#SvgImageSavingDelegate.SvgImageSavingDelegate.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invocato per ogni immagine SVG durante l'esportazione Markdown. |

### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Invocato per ogni immagine SVG durante l'esportazione Markdown. Restituisce true per utilizzare il collegamento specificato, oppure false per applicare la logica di salvataggio predefinita.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | L'immagine SVG esportata. |
| link | java.lang.String[] | Il collegamento Markdown da usare quando si restituisce true. |

**Restituisce:**
boolean