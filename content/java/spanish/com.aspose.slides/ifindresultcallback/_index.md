---
title: IFindResultCallback
second_title: Referencia de API de Aspose.Slides para Java
description: Interfaz de devolución de llamada utilizada para obtener el resultado de búsqueda de texto.
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