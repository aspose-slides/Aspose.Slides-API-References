---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /es/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## Métodos

| Método | Descripción |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | Callback que se invocará para cada [Slide](../../com.aspose.slides/slide), se espera que se devuelva la ruta de salida. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


Callback que se invocará para cada [Slide](../../com.aspose.slides/slide), se espera que se devuelva la ruta de salida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | Diapositiva iterada actual |
| index | int | Índice de la diapositiva actual |

**Devuelve:**
java.lang.String