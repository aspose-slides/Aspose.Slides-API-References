---
title: InkOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink σε εξαχόμενο έγγραφο.
type: docs
url: /el/com.aspose.slides/inkoptions/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink σε εξαχόμενο έγγραφο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHideInk()](#getHideInk--) | Εμφανίζει ή αποκρύπτει στοιχεία Ink σε εξαχόμενο έγγραφο. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Εμφανίζει ή αποκρύπτει στοιχεία Ink σε εξαχόμενο έγγραφο. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Χρησιμοποιεί την ενέργεια ROP ή Opacity για απόδοση πινέλου. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Χρησιμοποιεί την ενέργεια ROP ή Opacity για απόδοση πινέλου. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


Εμφανίζει ή αποκρύπτει στοιχεία Ink σε εξαχόμενο έγγραφο.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλεγμένη τιμή είναι false.

**Επιστρέφει:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


Εμφανίζει ή αποκρύπτει στοιχεία Ink σε εξαχόμενο έγγραφο.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλεγμένη τιμή είναι false.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```


Χρησιμοποιεί την ενέργεια ROP ή Opacity για απόδοση πινέλου.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλεγμένη τιμή είναι true.

**Επιστρέφει:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


Χρησιμοποιεί την ενέργεια ROP ή Opacity για απόδοση πινέλου.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Η προεπιλεγμένη τιμή είναι true.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |