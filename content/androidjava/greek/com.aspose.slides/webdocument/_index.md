---
title: WebDocument
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια μορφή μετάβασης της παρουσίασης για αποθήκευση σε μορφή ιστού.
type: docs
url: /el/com.aspose.slides/webdocument/
---
**Κληρονομικότητα:**
java.lang.Object
```
public class WebDocument
```

Αντιπροσωπεύει μια μορφή μετάβασης της παρουσίασης για αποθήκευση σε μορφή ιστού.
## Constructors

| Constructor | Description |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) κατασκευαστής. |
## Methods

| Method | Description |
| --- | --- |
| [save()](#save--) | Αποθηκεύει την έξοδο του εγγράφου. |
| [getInput()](#getInput--) | Επιστρέφει τη συλλογή των στοιχείων εισόδου (προτύπων) του εγγράφου. |
| [getOutput()](#getOutput--) | Επιστρέφει τη συλλογή των στοιχείων εξόδου του εγγράφου. |
| [getGlobal()](#getGlobal--) | Επιστρέφει τη γενική αποθήκευση του εγγράφου. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) κατασκευαστής.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Οι επιλογές που ορίζονται για το έγγραφο. |

### save() {#save--}
```
public final void save()
```


Αποθηκεύει την έξοδο του εγγράφου.

### getInput() {#getInput--}
```
public final Input getInput()
```


Επιστρέφει τη συλλογή των στοιχείων εισόδου (προτύπων) του εγγράφου. Μόνο για ανάγνωση [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Επιστρέφει:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Επιστρέφει τη συλλογή των στοιχείων εξόδου του εγγράφου. Μόνο για ανάγνωση [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // τοποθετήστε την ιδιότητα "slideMargin" για χρήση από τα πρότυπα
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... ρυθμίστε άλλες επιλογές του εγγράφου και στη συνέχεια αποθηκεύστε το έγγραφο
>   document.save();
> ```

**Επιστρέφει:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Επιστρέφει τη γενική αποθήκευση του εγγράφου. Μόνο για ανάγνωση [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // τοποθετήστε την ιδιότητα "slideMargin" για χρήση από τα πρότυπα
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... ρυθμίστε άλλες επιλογές του εγγράφου και στη συνέχεια αποθηκεύστε το έγγραφο
>   document.save();
> ```

**Επιστρέφει:**
[Storage](../../com.aspose.slides/storage)