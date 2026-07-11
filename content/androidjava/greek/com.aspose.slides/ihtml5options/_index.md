---
title: IHtml5Options
second_title: Aspose.Slides για Android μέσω Java API αναφορά
description: Αναπαριστά επιλογές εξαγωγής HTML5.
type: docs
url: /el/com.aspose.slides/ihtml5options/
---
**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Επιστρέφει ή ορίζει την επιλογή animation των μεταβάσεων. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Επιστρέφει ή ορίζει την επιλογή animation των μεταβάσεων. |
| [getAnimateShapes()](#getAnimateShapes--) | Επιστρέφει ή ορίζει την επιλογή animation των σχημάτων. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Επιστρέφει ή ορίζει την επιλογή animation των σχημάτων. |
| [getEmbedImages()](#getEmbedImages--) | Επιστρέφει ή ορίζει την επιλογή ενσωμάτωσης εικόνων. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Επιστρέφει ή ορίζει την επιλογή ενσωμάτωσης εικόνων. |
| [getOutputPath()](#getOutputPath--) | Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση συνδυασμών γραμμάτων. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση συνδυασμών γραμμάτων. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

Επιστρέφει ή ορίζει την επιλογή animation των μεταβάσεων. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

Επιστρέφει ή ορίζει την επιλογή animation των μεταβάσεων. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
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
public abstract boolean getAnimateShapes()
```

Επιστρέφει ή ορίζει την επιλογή animation των σχημάτων. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

Επιστρέφει ή ορίζει την επιλογή animation των σχημάτων. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
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
public abstract boolean getEmbedImages()
```

Επιστρέφει ή ορίζει την επιλογή ενσωμάτωσης εικόνων. Ανάγνωση/εγγραφή boolean.

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
public abstract void setEmbedImages(boolean value)
```

Επιστρέφει ή ορίζει την επιλογή ενσωμάτωσης εικόνων. Ανάγνωση/εγγραφή boolean.

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
public abstract String getOutputPath()
```

Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Ανάγνωση/εγγραφή String.

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
public abstract void setOutputPath(String value)
```

Καθορίζει πού πρέπει να αποθηκευτούν οι εξωτερικοί πόροι. Ανάγνωση/εγγραφή String.

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

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση συνδυασμών γραμμάτων. Όταν οριστεί σε true, οι συνδυασμοί γραμμάτων θα απενεργοποιηθούν στην έξοδο απόδοσης. Από προεπιλογή, αυτή η ιδιότητα είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Απενεργοποίηση συνδυασμών γραμμάτων στην απόδοση κειμένου
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
public abstract void setDisableFontLigatures(boolean value)
```

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς χρήση συνδυασμών γραμμάτων. Όταν οριστεί σε true, οι συνδυασμοί γραμμάτων θα απενεργοποιηθούν στην έξοδο απόδοσης. Από προεπιλογή, αυτή η ιδιότητα είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Απενεργοποίηση συνδυασμών γραμμάτων στην απόδοση κειμένου
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
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Λαμβάνει ή ορίζει τη λειτουργία με την οποία οι διαφάνειες τοποθετούνται στη σελίδα κατά την εξαγωγή μιας παρουσίασης [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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