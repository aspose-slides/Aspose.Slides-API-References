---
title: ExternalResourceResolver
second_title: Αναφορά API του Aspose.Slides για Java
description: Κλάση Callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html και Svg.
type: docs
url: /el/com.aspose.slides/externalresourceresolver/
---
**Κληρονομιά:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Κλάση Callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.

--------------------

Η χρήση αυτού του resolver μπορεί να δημιουργήσει ευπάθεια όταν ένα αρχείο HTML ή SVG που παρέχεται από τον πελάτη κάνει το λογισμικό του διακομιστή να αποκτήσει τοπικά ή δικτυακά αρχεία. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην καθορίζεται καθόλου το ExternalResourceResolver (θα διαβαστούν μόνο τα ενσωματωμένα αντικείμενα) ή να δημιουργηθεί κάποια υποκατηγορία που ελέγχει εάν το καθορισμένο uri είναι έγκυρο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Επιλύει το απόλυτο URI από τα βασικά και σχετικά URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Επιλύει το απόλυτο URI από τα βασικά και σχετικά URI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | java.lang.String | Βασικό URI των αντικειμένων σύνδεσης |
| relativeUri | java.lang.String | Σχετικό URI προς το συνδεδεμένο αντικείμενο. |

**Επιστρέφει:**
java.lang.String - Απόλυτο URI ή null εάν το σχετικό URI δεν μπορεί να επιλυθεί.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | java.lang.String | Απόλυτο URI προς το αντικείμενο. |

**Επιστρέφει:**
java.io.InputStream - Ένα αντικείμενο InputStream ή null εάν ο πόρος δεν μπορεί να μεταφερθεί.