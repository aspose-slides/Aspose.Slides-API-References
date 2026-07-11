---
title: SvgImage
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει μια εικόνα SVG.
type: docs
url: /el/com.aspose.slides/svgimage/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Αντιπροσωπεύει μια εικόνα SVG.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Δημιουργεί νέο αντικείμενο SvgImage. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Δημιουργεί νέο αντικείμενο SvgImage. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Δημιουργεί νέο αντικείμενο SvgImage. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί νέο αντικείμενο SvgImage. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί νέο αντικείμενο SvgImage. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Δημιουργεί νέο αντικείμενο SvgImage. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSvgData()](#getSvgData--) | Επιστρέφει δεδομένα SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Επιστρέφει το interface επανάκλησης που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Svg. |
| [getBaseUri()](#getBaseUri--) | Επιστρέφει το βασικό URI του καθορισμένου Svg. |
| [getSvgContent()](#getSvgContent--) | Επιστρέφει το περιεχόμενο SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Αποθηκεύει την εικόνα SVG ως αρχείο EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Δεδομένα Svg. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgContent | java.lang.String | Περιεχόμενο Svg. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή Svg. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Δεδομένα Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ένα αντικείμενο επανάκλησης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | java.lang.String | Βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgContent | java.lang.String | Περιεχόμενο Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ένα αντικείμενο επανάκλησης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | java.lang.String | Βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ένα αντικείμενο επανάκλησης που χρησιμοποιείται για την ανάκτηση εξωτερικών αντικειμένων. Εάν αυτή η παράμετρος είναι null όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | java.lang.String | Βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Επιστρέφει δεδομένα SVG. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Επιστρέφει το interface επανάκλησης που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Svg. Μόνο για ανάγνωση [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Επιστρέφει:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Επιστρέφει το βασικό URI του καθορισμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Επιστρέφει το περιεχόμενο SVG. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Αποθηκεύει την εικόνα SVG ως αρχείο EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Δημιουργεί τη νέα εικόνα SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Αποθηκεύει την εικόνα SVG ως αρχείο metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Δημιουργεί τη νέα εικόνα SVG
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Αποθηκεύει την εικόνα SVG ως αρχείο metafile
>      svgImage.writeAsEmf(byteStream);
>      // Προσθέτει το αρχείο metafile στη συλλογή εικόνων
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |