---
title: PdfImportOptions
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa las opciones de importación de PDF
type: docs
url: /es/com.aspose.slides/pdfimportoptions/
---
**Herencia:**
java.lang.Object
```
public class PdfImportOptions
```

Representa las opciones de importación de PDF
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Determina si detecta tablas al importar el archivo PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Determina si detecta tablas al importar el archivo PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Determina si detecta tablas al importar el archivo PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // establecer detección de tablas
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Determina si detecta tablas al importar el archivo PDF.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // establecer detección de tablas
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |