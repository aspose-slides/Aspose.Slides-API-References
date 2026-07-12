---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o manipulador de salvamento de imagem markdown do evento ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /pt/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representa o manipulador de salvamento de imagem markdown do evento \#ImageSavingDelegate.ImageSavingDelegate.

## Métodos

| Método | Descrição |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invocado para cada imagem não-SVG (bitmap ou metarquivo) durante a exportação Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Invoked for each non-SVG image (bitmap or metafile) during Markdown export. Return true to use the specified link, or false to apply the default saving logic.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | A imagem que está sendo exportada (bitmap ou metarquivo). |
| format | int | O formato da imagem. |
| link | java.lang.String[] | O link Markdown a ser usado ao retornar true. |

**Retorna:**
boolean