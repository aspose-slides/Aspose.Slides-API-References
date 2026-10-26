---
title: SaveOptions
second_title: Aspose.Slides για Android μέσω Αναφοράς Java API
description: Αφηρημένη κλάση με επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση.
type: docs
url: /el/com.aspose.slides/saveoptions/
---
**Κληρονομία:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Αφηρημένη κλάση με επιλογές που ελέγχουν πώς αποθηκεύεται μια παρουσίαση.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. |
| [getProgressCallback()](#getProgressCallback--) | Αναπαριστά ένα αντικείμενο callback για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Αναπαριστά ένα αντικείμενο callback για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η προεπιλεγμένη γραμματοσειρά δεν βρεθεί. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η προεπιλεγμένη γραμματοσειρά δεν βρεθεί. |
| [getGradientStyle()](#getGradientStyle--) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. |

### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Επιστρέφει:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Επιστρέφει ή ορίζει ένα αντικείμενο που λαμβάνει προειδοποιήσεις και αποφασίζει εάν η διαδικασία φόρτωσης θα συνεχιστεί ή θα ακυρωθεί. Ανάγνωση/εγγραφή [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

Αναπαριστά ένα αντικείμενο callback για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Επιστρέφει:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)

### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

Αναπαριστά ένα αντικείμενο callback για ενημερώσεις προόδου αποθήκευσης σε ποσοστό. Δείτε [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η προεπιλεγμένη γραμματοσειρά δεν βρεθεί. Ανάγνωση-εγγραφή String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Επιστρέφει ή ορίζει τη γραμματοσειρά που χρησιμοποιείται σε περίπτωση που η προεπιλεγμένη γραμματοσειρά δεν βρεθεί. Ανάγνωση-εγγραφή String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/εγγραφή [GradientStyle](../../com.aspose.slides/gradientstyle).

**Επιστρέφει:**
int

### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

Επιστρέφει ή ορίζει το οπτικό στυλ της διαβάθμισης. Ανάγνωση/εγγραφή [GradientStyle](../../com.aspose.slides/gradientstyle).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Όταν αυτή η ιδιότητα οριστεί σε true, οι υπερσυνδέσεις με κλήσεις JavaScript θα αγνοηθούν κατά την αποθήκευση.

Όταν αυτή η ιδιότητα οριστεί σε false, όλες οι υπερσυνδέσεις θα αποθηκευτούν.

**Επιστρέφει:**
boolean

### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

Καθορίζει εάν θα παραλειφθούν υπερσυνδέσεις με κλήσεις JavaScript κατά την αποθήκευση της παρουσίασης. Ανάγνωση/εγγραφή boolean. Η προεπιλεγμένη τιμή είναι false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Όταν αυτή η ιδιότητα οριστεί σε true, οι υπερσυνδέσεις με κλήσεις JavaScript θα αγνοηθούν κατά την αποθήκευση.

Όταν αυτή η ιδιότητα οριστεί σε false, όλες οι υπερσυνδέσεις θα αποθηκευτούν.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |