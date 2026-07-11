---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Επιλογές για την εξαγωγή HTML από το κείμενο του Pptx.
type: docs
url: /el/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Επιλογές για την εξαγωγή HTML από το κείμενο του Pptx.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Clipboard. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Clipboard. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Επιστρέφει ή ορίζει το βάθος κληρονομίας για τις ιδιότητες κειμένου. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Επιστρέφει ή ορίζει το βάθος κληρονομίας για τις ιδιότητες κειμένου. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. |
| [getEncodingName()](#getEncodingName--) | Επιστρέφει ή ορίζει το όνομα κωδικοποίησης html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Επιστρέφει ή ορίζει το όνομα κωδικοποίησης html. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Clipboard. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Επιστρέφει ή ορίζει τιμή, υποδεικνύοντας αν πρέπει να προστεθούν κεφαλίδες Clipboard. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Επιστρέφει ή ορίζει το βάθος κληρονομίας για τις ιδιότητες κειμένου. Ανάγνωση/εγγραφή [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Επιστρέφει:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Επιστρέφει ή ορίζει το βάθος κληρονομίας για τις ιδιότητες κειμένου. Ανάγνωση/εγγραφή [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. Ανάγνωση/εγγραφή [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Επιστρέφει:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Επιστρέφει ή ορίζει ένα αντικείμενο callback που ελέγχει πώς θα αποθηκευτεί το εξωτερικό αντικείμενο. Ανάγνωση/εγγραφή [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Επιστρέφει ή ορίζει το όνομα κωδικοποίησης html. Αυτή η τιμή θα αποθηκευτεί στο παραγόμενο αρχείο HTML, αλλά εξαρτάται από τον καλούντα να διασφαλίσει ότι το αρχείο θα αποθηκευτεί σε αυτήν την κωδικοποίηση. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Επιστρέφει ή ορίζει το όνομα κωδικοποίησης html. Αυτή η τιμή θα αποθηκευτεί στο παραγόμενο αρχείο HTML, αλλά εξαρτάται από τον καλούντα να διασφαλίσει ότι το αρχείο θα αποθηκευτεί σε αυτήν την κωδικοποίηση. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |