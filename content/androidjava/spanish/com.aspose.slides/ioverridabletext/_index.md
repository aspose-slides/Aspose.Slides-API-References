---
title: IOverridableText
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa texto sobrescribible para un gráfico.
type: docs
url: /es/com.aspose.slides/ioverridabletext/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Representa texto sobrescribible para un gráfico.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Puede contener un texto con formato enriquecido. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializa TextFrameForOverriding con el texto en el parámetro "text". |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```


Puede contener un texto con formato enriquecido. Si esta propiedad no es nula, entonces este valor de texto formateado sobrescribe el texto generado automáticamente. El texto generado automáticamente es una propiedad implícita de la etiqueta de datos, la etiqueta de unidad de visualización del eje de valores, el título del eje, el título del gráfico, la etiqueta de la línea de tendencia. El texto generado automáticamente se formatea con la propiedad IFormattedTextContainer.TextFormat. Solo lectura [ITextFrame](../../com.aspose.slides/itextframe).

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```


Inicializa TextFrameForOverriding con el texto en el parámetro "text". Si TextFrameForOverriding ya está inicializado, simplemente cambia su texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto para un nuevo TextFrameForOverriding. |

**Devuelve:**
[ITextFrame](../../com.aspose.slides/itextframe) - Marco de texto [ITextFrame](../../com.aspose.slides/itextframe)