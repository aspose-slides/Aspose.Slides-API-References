---
title: TextToHtmlConversionOptions
second_title: Αναφορά API του Aspose.Slides για Java
description: Επιλογές για την εξαγωγή HTML από το κείμενο του Pptx.
type: docs
url: /el/com.aspose.slides/texttohtmlconversionoptions/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Επιλογές για την εξαγωγή HTML από το κείμενο του Pptx.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Πρόχειρου. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Πρόχειρου. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Επιστρέφει ή ορίζει το βάθος κληρονόμησης για ιδιότητες κειμένου. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Επιστρέφει ή ορίζει το βάθος κληρονόμησης για ιδιότητες κειμένου. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. |
| [getEncodingName()](#getEncodingName--) | Επιστρέφει ή ορίζει το όνομα κωδικοποίησης HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα κωδικοποίησης HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Πρόχειρου. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Πρόχειρου. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Επιστρέφει ή ορίζει το βάθος κληρονόμησης για ιδιότητες κειμένου. Ανάγνωση/εγγραφή [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Επιστρέφει:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Επιστρέφει ή ορίζει το βάθος κληρονόμησης για ιδιότητες κειμένου. Ανάγνωση/εγγραφή [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. Ανάγνωση/εγγραφή [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Επιστρέφει:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. Ανάγνωση/εγγραφή [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Επιστρέφει ή ορίζει το όνομα κωδικοποίησης HTML. Αυτή η τιμή θα αποθηκευτεί στο παραγόμενο αρχείο HTML, αλλά εξαρτάται από τον καλούντα να διασφαλίσει ότι το αρχείο θα αποθηκευτεί με αυτήν την κωδικοποίηση. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Επιστρέφει ή ορίζει το όνομα κωδικοποίησης HTML. Αυτή η τιμή θα αποθηκευτεί στο παραγόμενο αρχείο HTML, αλλά εξαρτάται από τον καλούντα να διασφαλίσει ότι το αρχείο θα αποθηκευτεί με αυτήν την κωδικοποίηση. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |