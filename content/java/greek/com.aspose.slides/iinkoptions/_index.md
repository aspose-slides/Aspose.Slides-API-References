---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Provides options that control the look of Ink objects in exported document.
type: docs
url: /el/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getHideInk()](#getHideInk--) | Εμφανίζει ή αποκρύπτει τα στοιχεία Ink στο εξαγόμενο έγγραφο. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Εμφανίζει ή αποκρύπτει τα στοιχεία Ink στο εξαγόμενο έγγραφο. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Χρησιμοποιεί λειτουργία ROP ή διαφάνεια για την απόδοση του πινέλου. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Χρησιμοποιεί λειτουργία ROP ή διαφάνεια για την απόδοση του πινέλου. |

### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

Εμφανίζει ή αποκρύπτει τα στοιχεία Ink στο εξαγόμενο έγγραφο.

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
public abstract void setHideInk(boolean value)
```

Εμφανίζει ή αποκρύπτει τα στοιχεία Ink στο εξαγόμενο έγγραφο.

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
public abstract boolean getInterpretMaskOpAsOpacity()
```

Χρησιμοποιεί λειτουργία ROP ή διαφάνεια για την απόδοση του πινέλου.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

Χρησιμοποιεί λειτουργία ROP ή διαφάνεια για την απόδοση του πινέλου.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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