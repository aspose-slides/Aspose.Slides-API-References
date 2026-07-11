---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /el/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Αντιπροσωπεύει μια εικόνα SVG.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Επιστρέφει το περιεχόμενο SVG. |
| [getSvgData()](#getSvgData--) | Επιστρέφει τα δεδομένα SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Επιστρέφει τη διασύνδεση callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων SVG. |
| [getBaseUri()](#getBaseUri--) | Επιστρέφει το βασικό URI του καθορισμένου SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Αποθηκεύει την εικόνα SVG ως αρχείο EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

Επιστρέφει το περιεχόμενο SVG. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

Επιστρέφει τα δεδομένα SVG. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

Επιστρέφει τη διασύνδεση callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων SVG. Μόνο για ανάγνωση [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Επιστρέφει:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

Επιστρέφει το βασικό URI του καθορισμένου SVG. Χρησιμοποιείται για την επίλυση σχετικών συνδέσμων. Μόνο για ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Αποθηκεύει την εικόνα SVG ως αρχείο EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // Δημιουργεί τη νέα εικόνα SVG
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Αποθηκεύει την εικόνα SVG ως μετααρχείο
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
>      // Αποθηκεύει την εικόνα SVG ως μετααρχείο
>      svgImage.writeAsEmf(byteStream);
>      // Προσθέτει το μετααρχείο στη συλλογή εικόνων
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Στόχος ροής |