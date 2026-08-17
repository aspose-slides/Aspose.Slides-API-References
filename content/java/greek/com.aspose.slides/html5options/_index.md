---
title: Html5Options
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει επιλογές εξαγωγής HTML5.
type: docs
url: /el/com.aspose.slides/html5options/
---
**Κληρονομικότητα:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

Αντιπροσωπεύει επιλογές εξαγωγής HTML5.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Html5Options()](#Html5Options--) | Προεπιλεγμένος κατασκευαστής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Επιστρέφει ή ρυθμίζει την επιλογή κίνησης μεταβάσεων. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Επιστρέφει ή ρυθμίζει την επιλογή κίνησης μεταβάσεων. |
| [getAnimateShapes()](#getAnimateShapes--) | Επιστρέφει ή ρυθμίζει την επιλογή κίνησης σχημάτων. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Επιστρέφει ή ρυθμίζει την επιλογή κίνησης σχημάτων. |
| [getEmbedImages()](#getEmbedImages--) | Επιστρέφει ή ρυθμίζει την επιλογή ενσωμάτωσης εικόνων. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Επιστρέφει ή ρυθμίζει την επιλογή ενσωμάτωσης εικόνων. |
| [getOutputPath()](#getOutputPath--) | Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. |
| [getPicturesCompression()](#getPicturesCompression--) | Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Λαμβάνει ή ρυθμίζει μια τιμή που υποδεικνύει εάν το κείμενο αποτυπώνεται χωρίς χρήση συνδέσεων (ligatures). |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Λαμβάνει ή ρυθμίζει μια τιμή που υποδεικνύει εάν το κείμενο αποτυπώνεται χωρίς χρήση συνδέσεων (ligatures). |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ρυθμίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ρυθμίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

Προεπιλεγμένος κατασκευαστής.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

Επιστρέφει ή ρυθμίζει την επιλογή κίνησης μεταβάσεων. Αναγνώσιμο/εγγράψιμο boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

Επιστρέφει ή ρυθμίζει την επιλογή κίνησης μεταβάσεων. Αναγνώσιμο/εγγράψιμο boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

Επιστρέφει ή ρυθμίζει την επιλογή κίνησης σχημάτων. Αναγνώσιμο/εγγράψιμο boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

Επιστρέφει ή ρυθμίζει την επιλογή κίνησης σχημάτων. Αναγνώσιμο/εγγράψιμο boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

Επιστρέφει ή ρυθμίζει την επιλογή ενσωμάτωσης εικόνων. Αναγνώσιμο/εγγράψιμο boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

Επιστρέφει ή ρυθμίζει την επιλογή ενσωμάτωσης εικόνων. Αναγνώσιμο/εγγράψιμο boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Αναγνώσιμο/εγγράψιμο String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Αναγνώσιμο/εγγράψιμο String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων

**Επιστρέφει:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Αντιπροσωπεύει το επίπεδο συμπίεσης εικόνων

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Λαμβάνει ή ρυθμίζει μια τιμή που υποδεικνύει εάν το κείμενο αποτυπώνεται χωρίς χρήση συνδέσεων (ligatures). Όταν ορίζεται σε true, οι συνδέσεις θα απενεργοποιηθούν στο αποτυπωμένο αποτέλεσμα. Προεπιλεγμένα, αυτή η ιδιότητα είναι ορισμένη σε false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Απενεργοποίηση συνδέσεων κατά την απόδοση κειμένου
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Επιστρέφει:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Λαμβάνει ή ρυθμίζει μια τιμή που υποδεικνύει εάν το κείμενο αποτυπώνεται χωρίς χρήση συνδέσεων (ligatures). Όταν ορίζεται σε true, οι συνδέσεις θα απενεργοποιηθούν στο αποτυπωμένο αποτέλεσμα. Προεπιλεγμένα, αυτή η ιδιότητα είναι ορισμένη σε false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Απενεργοποίηση συνδέσεων κατά την απόδοση κειμένου
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Λαμβάνει ή ρυθμίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Λαμβάνει ή ρυθμίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |