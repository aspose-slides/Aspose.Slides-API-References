---
title: PdfImportOptions
second_title: Aspose.Slides Android के लिए, Java API रेफ़रेंस के माध्यम से
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
## कन्स्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | निर्धारित करता है कि PDF फ़ाइल आयात करते समय तालिकाओं का पता लगाया जाए या नहीं। |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | निर्धारित करता है कि PDF फ़ाइल आयात करते समय तालिकाओं का पता लगाया जाए या नहीं। |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

निर्धारित करता है कि PDF फ़ाइल आयात करते समय तालिकाओं का पता लगाया जाए या नहीं।

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
>          // टेबलों का पता लगाना सेट करें
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

निर्धारित करता है कि PDF फ़ाइल आयात करते समय तालिकाओं का पता लगाया जाए या नहीं।

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
>          // टेबलों का पता लगाना सेट करें
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |