---
title: Convert
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για τη μετατροπή.
type: docs
url: /el/com.aspose.slides/convert/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class Convert
```

Αντιπροσωπεύει μια ομάδα μεθόδων που προορίζονται για τη μετατροπή του [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Convert()](#Convert--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) χρησιμοποιώντας την παρεχόμενη επέκταση διαδρομής εξόδου για να προσδιορίσει την απαιτούμενη μορφή εξαγωγής. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής PNG. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Μετατρέπει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Μετατρέπει την παρουσίαση εισόδου σε μορφή TIFF με προσαρμοσμένες επιλογές. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) χρησιμοποιώντας την παρεχόμενη επέκταση διαδρομής εξόδου για να προσδιορίσει την απαιτούμενη μορφή εξαγωγής.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | java.lang.String | Διαδρομή της παρουσίασης εισόδου |
| outPath | java.lang.String | Διαδρομή εξόδου |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | java.lang.String | Διαδρομή της παρουσίασης εισόδου |
| outPath | java.lang.String | Διαδρομή εξόδου |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | java.lang.String | Διαδρομή της παρουσίασης εισόδου |
| outPath | java.lang.String | Διαδρομή εξόδου |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Επιλογές εξόδου PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Παρουσίαση εισόδου |
| outPath | java.lang.String | Διαδρομή εξόδου |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.setCompliance(PdfCompliance.PdfUa);
>      Convert.toPdf(pres, "output.pdf", pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Παρουσίαση εισόδου |
| outPath | java.lang.String | Διαδρομή εξόδου |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Επιλογές εξόδου PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | java.lang.String | Διαδρομή της παρουσίασης εισόδου |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| presPath | java.lang.String | Διαδρομή της παρουσίασης εισόδου |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Αντιστροφή κλήσης που επιστρέφει τη διαδρομή εξόδου SVG για κάθε διαφάνεια στην παρουσίαση |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Παρουσίαση εισόδου |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Αντιστροφή κλήσης που επιστρέφει τη διαδρομή εξόδου SVG για κάθε διαφάνεια στην παρουσίαση |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Παρουσίαση εισόδου |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Επιλογές εξαγωγής SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```


Μετατρέπει το [Presentation](../../com.aspose.slides/presentation) σε SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Παρουσίαση εισόδου |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Αντιστροφή κλήσης που επιστρέφει τη διαδρομή εξόδου SVG για κάθε διαφάνεια στην παρουσίαση |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Επιλογές εξαγωγής SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής JPEG. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής JPEG. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |
| imageSize | java.awt.Dimension | Το μέγεθος κάθε δημιουργημένης εικόνας. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής JPEG. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.jpeg", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.jpeg", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |
| scale | float | Ο συντελεστής κλιμάκωσης που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Οι επιλογές απόδοσης. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής PNG. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.png", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.png", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής PNG. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.png", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.png", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |
| imageSize | java.awt.Dimension | Το μέγεθος κάθε δημιουργημένης εικόνας. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής PNG. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.png", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.png", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |
| scale | float | Ο συντελεστής κλιμάκωσης που εφαρμόζεται στις εικόνες εξόδου σε σχέση με το αρχικό μέγεθος της διαφάνειας. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Οι επιλογές απόδοσης. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Μετατίνει την παρουσίαση εισόδου σε ένα σύνολο εικόνων μορφής TIFF. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.tiff", το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.tiff", όπου N είναι ο αριθμός της διαφάνειας.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Μετατίνει την παρουσίαση εισόδου σε μορφή TIFF με προσαρμοσμένες επιλογές. Εάν το όνομα αρχείου εξόδου δίνεται ως "myPath/myFilename.tiff" και multipage είναι false, το αποτέλεσμα θα αποθηκευτεί ως ένα σύνολο αρχείων "myPath/myFilename\_N.tiff", όπου N είναι ο αριθμός της διαφάνειας. Διαφορετικά, εάν multipage είναι true, το αποτέλεσμα θα είναι ένα πολυσέλιδο έγγραφο "myPath/myFilename.tiff".

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  ITiffOptions options = new TiffOptions();
>  options.setCompressionType(TiffCompressionTypes.CCITT3);
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "pres.tiff", options, false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Η παρουσίαση εισόδου. |
| outputFileName | java.lang.String | Το όνομα αρχείου εξόδου. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Οι επιλογές αποθήκευσης TIFF. |
| multipage | boolean | Καθορίζει εάν το παραγόμενο έγγραφο TIFF πρέπει να είναι multi-page. |