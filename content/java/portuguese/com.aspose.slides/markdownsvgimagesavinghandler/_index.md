---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown SVG image saving handler of SvgImageSavingDelegate.SvgImageSavingDelegate event.
type: docs
url: /pt/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

Representa o manipulador de salvamento de imagem SVG em markdown do evento #SvgImageSavingDelegate.SvgImageSavingDelegate.

## Métodos

| Método | Descrição |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Invocado para cada imagem SVG durante a exportação Markdown. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```


Invocado para cada imagem SVG durante a exportação Markdown. Retorne true para usar o link especificado, ou false para aplicar a lógica de salvamento padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | A imagem SVG que está sendo exportada. |
| link | java.lang.String[] | O link Markdown a ser usado ao retornar true. |

**Retorna:**
boolean