---
title: IPptxOptions
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει επιλογές για την αποθήκευση παρουσιάσεων OpenXml PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /el/com.aspose.slides/ipptxoptions/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Αντιπροσωπεύει επιλογές για την αποθήκευση παρουσιάσεων OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getConformance()](#getConformance--) | Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Presentation. |
| [setConformance(int value)](#setConformance-int-) | Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Καθορίζει εάν θα ανανεωθεί η μικρογραφία της παρουσίασης. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Καθορίζει εάν θα ανανεωθεί η μικρογραφία της παρουσίασης. |
| [getCompressionLevel()](#getCompressionLevel--) | Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Presentation. Η προεπιλεγμένη τιμή είναι [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Επιστρέφει:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Καθορίζει την κλάση συμμόρφωσης στην οποία συμμορφώνεται το έγγραφο Presentation. Η προεπιλεγμένη τιμή είναι [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Presentation. Η προεπιλεγμένη τιμή είναι [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

Καθορίζει εάν χρησιμοποιείται η μορφή ZIP64 για το έγγραφο Presentation. Η προεπιλεγμένη τιμή είναι [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract boolean getRefreshThumbnail()
```

Καθορίζει εάν θα ανανεωθεί η μικρογραφία της παρουσίασης. Λογική ανάγνωση/γραφή. Η προεπιλεγμένη τιμή είναι **true**.

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

Όταν η τιμή της επιλογής είναι **true**, θα δημιουργηθεί η νέα μικρογραφία.

Όταν η τιμή της επιλογής είναι **false**, η τρέχουσα μικρογραφία θα αποθηκευθεί όπως είναι.

**Επιστρέφει:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Καθορίζει εάν θα ανανεωθεί η μικρογραφία της παρουσίασης. Λογική ανάγνωση/γραφή. Η προεπιλεγμένη τιμή είναι **true**.

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

Όταν η τιμή της επιλογής είναι **true**, θα δημιουργηθεί η νέα μικρογραφία.

Όταν η τιμή της επιλογής είναι **false**, η τρέχουσα μικρογραφία θα αποθηκευθεί όπως είναι.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
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

Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία, αλλά απαιτούν περισσότερο χρόνο επεξεργασίας. Η πραγματική αναλογία συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης.

**Επιστρέφει:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
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

Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία, αλλά απαιτούν περισσότερο χρόνο επεξεργασίας. Η πραγματική αναλογία συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |