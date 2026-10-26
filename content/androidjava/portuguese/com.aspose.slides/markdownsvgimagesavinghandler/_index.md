---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android via Java API Reference
description: Representa o manipulador de salvamento de imagens SVG em markdown do SvgImageSavingDelegate.SvgImageSavingDelegate evento.
type: docs
url: /pt/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Representa o manipulador de salvamento de imagens SVG em markdown do \#SvgImageSavingDelegate.SvgImageSavingDelegate evento.
## Métodos

| Método | Descrição |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invocado para cada imagem SVG durante a exportação Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Invocado para cada imagem SVG durante a exportação Markdown. Retorne true para usar o link especificado, ou false para aplicar a lógica padrão de salvamento.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | A imagem SVG que está sendo exportada. |
| link | java.lang.String[] | O link Markdown a ser usado ao retornar true. |

**Retorna:**
boolean