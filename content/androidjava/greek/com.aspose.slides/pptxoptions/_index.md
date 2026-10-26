---
title: PptxOptions
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αντιπροσωπεύει τις επιλογές για αποθήκευση παρουσιάσεων OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /el/com.aspose.slides/pptxoptions/
---
**Κληρονομία:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Αντιπροσωπεύει τις επιλογές για αποθήκευση παρουσιάσεων OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Δημιουργεί νέο στιγμιότυπο του PptxOptions |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getConformance()](#getConformance--) | Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Παρουσίασης. |
| [setConformance(int value)](#setConformance-int-) | Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Παρουσίασης. |
| [getZip64Mode()](#getZip64Mode--) | Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Παρουσίασης. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Παρουσίασης. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Καθορίζει εάν το μικρογραφικό της παρουσίασης θα ανανεωθεί. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Καθορίζει εάν το μικρογραφικό της παρουσίασης θα ανανεωθεί. |
| [getCompressionLevel()](#getCompressionLevel--) | Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Δημιουργεί νέο στιγμιότυπο του PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Παρουσίασης. Η προεπιλεγμένη τιμή είναι [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Επιστρέφει:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Παρουσίασης. Η προεπιλεγμένη τιμή είναι [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Παρουσίασης. Η προεπιλεγμένη τιμή είναι [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Παρουσίασης. Η προεπιλεγμένη τιμή είναι [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Καθορίζει εάν το μικρογραφικό της παρουσίασης θα ανανεωθεί. Αναγνώσιμη/εγγράψιμη boolean. Η προεπιλεγμένη τιμή είναι **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Όταν η τιμή της επιλογής είναι **true**, θα δημιουργηθεί νέο μικρογραφικό.

Όταν η τιμή της επιλογής είναι **false**, το υπάρχον μικρογραφικό θα αποθηκευτεί όπως είναι.

**Επιστρέφει:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Καθορίζει εάν το μικρογραφικό της παρουσίασης θα ανανεωθεί. Αναγνώσιμη/εγγράψιμη boolean. Η προεπιλεγμένη τιμή είναι **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Όταν η τιμή της επιλογής είναι **true**, θα δημιουργηθεί νέο μικρογραφικό.

Όταν η τιμή της επιλογής είναι **false**, το υπάρχον μικρογραφικό θα αποθηκευτεί όπως είναι.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία αλλά απαιτούν περισσότερο χρόνο επεξεργασίας. Ο πραγματικός λόγος συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης.

**Επιστρέφει:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία αλλά απαιτούν περισσότερο χρόνο επεξεργασίας. Ο πραγματικός λόγος συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |