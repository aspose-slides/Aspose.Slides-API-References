---
title: PdfImportOptions
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa as opções de importação de PDF
type: docs
url: /pt/com.aspose.slides/pdfimportoptions/
---
**Herança:**
java.lang.Object
```
public class PdfImportOptions
```

Representa as opções de importação de PDF
## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Determina se detecta tabelas ao importar o arquivo PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Determina se detecta tabelas ao importar o arquivo PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Determina se detecta tabelas ao importar o arquivo PDF.

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
>          // definir detecção de tabelas
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Determina se detecta tabelas ao importar o arquivo PDF.

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
>          // definir detecção de tabelas
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |