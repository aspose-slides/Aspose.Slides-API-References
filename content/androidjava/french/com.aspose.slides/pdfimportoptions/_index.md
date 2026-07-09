---
title: PdfImportOptions
second_title: Référence de l'API Aspose.Slides pour Android via Java
description: Représente les options d'importation PDF
type: docs
url: /fr/com.aspose.slides/pdfimportoptions/
---
**Héritage :**
java.lang.Object
```
public class PdfImportOptions
```

Représente les options d'importation PDF
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Détermine si les tables sont détectées lors de l'importation du fichier PDF. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Détermine si les tables sont détectées lors de l'importation du fichier PDF. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Détermine si les tables sont détectées lors de l'importation du fichier PDF.

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
>          // activer la détection des tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public final void setDetectTables(boolean value)


Détermine si les tables sont détectées lors de l'importation du fichier PDF.

--------------------

> ```
> Exemple :
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // set detecting tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |