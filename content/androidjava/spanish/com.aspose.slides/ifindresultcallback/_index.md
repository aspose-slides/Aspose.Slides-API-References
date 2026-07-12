---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /es/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Interfaz de devolución de llamada utilizada para obtener el resultado de búsqueda de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Método de devolución de llamada que recibe datos sobre el texto encontrado. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Método de devolución de llamada que recibe datos sobre el texto encontrado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | El [ITextFrame](../../com.aspose.slides/itextframe) en el que se encontró el texto. |
| sourceText | java.lang.String | El texto fuente en el que se encontró el texto. |
| foundText | java.lang.String | El texto encontrado. |
| textPosition | int | La posición del texto encontrado. |