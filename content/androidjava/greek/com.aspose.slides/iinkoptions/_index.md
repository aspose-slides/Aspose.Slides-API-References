---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.
type: docs
url: /el/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Παρέχει επιλογές που ελέγχουν την εμφάνιση των αντικειμένων Ink στο εξαγόμενο έγγραφο.
## Methods

| Method | Description |
| --- | --- |
| [getHideInk()](#getHideInk--) | Εμφανίζει ή αποκρύπτει στοιχεία Ink στο εξαγόμενο έγγραφο. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Εμφανίζει ή αποκρύπτει στοιχεία Ink στο εξαγόμενο έγγραφο. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Χρησιμοποιεί λειτουργία ROP ή Αδιαφάνεια για το πινέλο απόδοσης. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Χρησιμοποιεί λειτουργία ROP ή Αδιαφάνεια για το πινέλο απόδοσης. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

Εμφανίζει ή αποκρύπτει στοιχεία Ink στο εξαγόμενο έγγραφο.

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

**Returns:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

Εμφανίζει ή αποκρύπτει στοιχεία Ink στο εξαγόμενο έγγραφο.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

Χρησιμοποιεί λειτουργία ROP ή Αδιαφάνεια για το πινέλο απόδοσης.

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

**Returns:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

Χρησιμοποιεί λειτουργία ROP ή Αδιαφάνεια για το πινέλο απόδοσης.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |