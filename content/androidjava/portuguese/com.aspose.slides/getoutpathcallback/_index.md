---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /pt/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Métodos

| Método | Descrição |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Callback que será invocado para cada [Slide](../../com.aspose.slides/slide), o caminho de saída esperado a ser retornado. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

Callback que será invocado para cada [Slide](../../com.aspose.slides/slide), o caminho de saída esperado a ser retornado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Slide iterado atual |
| index | int | Índice do slide atual |

**Retorna:**
java.lang.String