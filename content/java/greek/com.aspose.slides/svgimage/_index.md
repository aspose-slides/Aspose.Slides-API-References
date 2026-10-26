---
title: SvgImage
second_title: Aspose.Slides για Java Αναφορά API
description: Αναπαριστά μια εικόνα SVG.
type: docs
url: /el/com.aspose.slides/svgimage/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Αναπαριστά μια εικόνα SVG.
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
| [getSvgData()](#getSvgData--) | Επιστρέφει τα δεδομένα SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Επιστρέφει τη διεπαφή επανάκλησης που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Svg. |
| [getBaseUri()](#getBaseUri--) | Επιστρέφει το βασικό URI του συγκεκριμένου Svg. |
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
| data | byte[] | Δεδομένα SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgContent | java.lang.String | Περιεχόμενο SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | byte[] | Δεδομένα SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο επανάκλησης που χρησιμοποιείται για τη λήψη εξωτερικών αντικειμένων. Αν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | java.lang.String | Βασικό URI του συγκεκριμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgContent | java.lang.String | Περιεχόμενο SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο επανάκλησης που χρησιμοποιείται για τη λήψη εξωτερικών αντικειμένων. Αν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | java.lang.String | Βασικό URI του συγκεκριμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

Δημιουργεί νέο αντικείμενο SvgImage.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ροή SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Αντικείμενο επανάκλησης που χρησιμοποιείται για τη λήψη εξωτερικών αντικειμένων. Αν αυτή η παράμετρος είναι null, όλα τα εξωτερικά αντικείμενα θα αγνοηθούν. |
| baseUri | java.lang.String | Βασικό URI του συγκεκριμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

Επιστρέφει τα δεδομένα SVG. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

Επιστρέφει τη διεπαφή επανάκλησης που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Svg. Μόνο για ανάγνωση [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Επιστρέφει:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

Επιστρέφει το βασικό URI του συγκεκριμένου Svg. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. Μόνο για ανάγνωση String.

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
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Ροή προορισμού |