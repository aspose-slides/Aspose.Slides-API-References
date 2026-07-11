---
title: XpsOptions
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή XPS.
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

Παρέχει επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση σε μορφή XPS.

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
>      // Δημιουργήστε την κλάση TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Αποθήκευση MetaFiles ως PNG
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
| [XpsOptions()](#XpsOptions--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυμμένες διαφάνειες ή όχι. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυμμένες διαφάνειες ή όχι. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | **true** για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται στην παρουσίαση σε εικόνες PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | **true** για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται στην παρουσίαση σε εικόνες PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | **true** για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | **true** για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

Προεπιλεγμένος κατασκευαστής.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυμμένες διαφάνειες ή όχι. Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Καθορίζει εάν το παραγόμενο έγγραφο θα περιλαμβάνει κρυμμένες διαφάνειες ή όχι. Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

**true** για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται στην παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **true**.

**Επιστρέφει:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

**true** για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται στην παρουσίαση σε εικόνες PNG. Ανάγνωση/εγγραφή boolean.

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

**true** για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Επιστρέφει:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

**true** για σχεδίαση μαύρου πλαισίου γύρω από κάθε διαφάνεια. Ανάγνωση/εγγραφή boolean.

--------------------

Η προεπιλογή είναι **false**.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |