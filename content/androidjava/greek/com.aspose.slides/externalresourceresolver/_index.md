---
title: ExternalResourceResolver
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Κλάση Callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html και Svg.
type: docs
url: /el/com.aspose.slides/externalresourceresolver/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι υλοποιημένες διεπαφές:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Κλάση Callback που χρησιμοποιείται για την επίλυση εξωτερικών πόρων κατά την εισαγωγή εγγράφων Html, Svg.

--------------------

Η χρήση αυτού του επιλυτή μπορεί να δημιουργήσει ευπάθεια όταν ένα αρχείο HTML ή SVG που παρέχεται από τον πελάτη επιτρέπει στο λογισμικό του διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην καθορίζετε το ExternalResourceResolver καθόλου (μόνο τα ενσωματωμένα αντικείμενα θα διαβαστούν) ή να δημιουργήσετε κάποιο υποκλάσσο που ελέγχει αν το καθορισμένο uri είναι έγκυρο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Επιλύει το απόλυτο URI από τα βασικά και σχετικά URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Επιλύει το απόλυτο URI από τα βασικά και σχετικά URIs.

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


Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | java.lang.String | Απόλυτο URI προς το αντικείμενο. |

**Επιστρέφει:**
java.io.InputStream - Ένα αντικείμενο InputStream ή null εάν ο πόρος δεν μπορεί να μεταδοθεί.