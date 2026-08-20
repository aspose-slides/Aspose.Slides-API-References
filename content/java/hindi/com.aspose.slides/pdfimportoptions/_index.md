---
title: PdfImportOptions
second_title: Aspose.Slides जावा के लिए API रेफ़रेंस
description: PDF आयात विकल्पों का प्रतिनिधित्व करता है
type: docs
url: /hi/com.aspose.slides/pdfimportoptions/
---
**विरासत:**
java.lang.Object
```
public class PdfImportOptions
```

PDF आयात विकल्पों का प्रतिनिधित्व करता है
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Determines whether detect tables when importing pdf file. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Determines whether detect tables when importing pdf file. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


PDF फ़ाइल आयात करते समय टेबल की पहचान करे या नहीं निर्धारित करता है।

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
>          // टेबल की पहचान सेट करें
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


PDF फ़ाइल आयात करते समय टेबल की पहचान करे या नहीं निर्धारित करता है।

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
>          // टेबल की पहचान सेट करें
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |