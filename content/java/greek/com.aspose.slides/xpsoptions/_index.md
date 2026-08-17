---
title: XpsOptions
second_title: Aspose.Slides για την αναφορά API της Java
description: Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή XPS.
type: docs
url: /el/com.aspose.slides/xpsoptions/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Παρέχει επιλογές που ελέγχουν τον τρόπο αποθήκευσης μιας παρουσίασης σε μορφή XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Αποθήκευση της παρουσίασης σε έγγραφο XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Δημιουργήστε ένα αντικείμενο Presentation που αντιπροσωπεύει ένα αρχείο παρουσίασης
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Δημιουργήστε ένα αντικείμενο της κλάσης TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Αποθήκευση των MetaFiles ως PNG
>      options.setSaveMetafilesAsPng(true);
>      // Αποθήκευση της παρουσίασης σε έγγραφο XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Κατασκευαστής προεπιλογής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει αν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει αν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True για τη σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True για τη σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Κατασκευαστής προεπιλογής.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Καθορίζει αν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει αν το παραγόμενο έγγραφο θα περιλαμβάνει κρυφές διαφάνειες ή όχι. Η προεπιλογή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

True για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

True για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

True για τη σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

True για τη σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |