---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Representa o manipulador de salvar imagens markdown do evento ImageSavingDelegate.ImageSavingDelegate.
type: docs
url: /pt/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

Representa o manipulador de salvar imagens markdown do evento \#ImageSavingDelegate.ImageSavingDelegate.

## Métodos

| Method | Description |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Invocado para cada imagem não SVG (bitmap ou metafile) durante a exportação Markdown. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Invocado para cada imagem não SVG (bitmap ou metafile) durante a exportação Markdown. Retorne true para usar o link especificado, ou false para aplicar a lógica padrão de salvamento.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | A imagem sendo exportada (bitmap ou metafile). |
| format | int | O formato da imagem. |
| link | java.lang.String[] | O link Markdown a ser usado quando for retornado true. |

**Retorna:**
boolean