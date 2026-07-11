---
title: HtmlExternalResolver
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντικείμενο Callback που χρησιμοποιείται από τη διαδικασία εισαγωγής HTML για την απόκτηση αναφερθέντων αντικειμένων όπως εικόνες.
type: docs
url: /el/com.aspose.slides/htmlexternalresolver/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Αντικείμενο αντιστροφής που χρησιμοποιείται από τη διαδικασία εισαγωγής HTML για την απόκτηση αναφερθέντων αντικειμένων όπως εικόνες.

--------------------

Η χρήση αυτού του επιλυτή μπορεί να δημιουργήσει ευπάθεια όταν το αρχείο HTML που παρέχεται από τον πελάτη κάνει το λογισμικό διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην καθορίζετε καθόλου HtmlExternalResolver (θα διαβαστούν μόνο τα ενσωματωμένα αντικείμενα) ή να δημιουργήσετε κάποιο υποκατηγόρημα που ελέγχει εάν το καθορισμένο uri είναι έγκυρο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Επιστρέφει το απόλυτο URI από τα βασικά και σχετικά URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Χαρτογραφεί ένα URI σε αντικείμενο που περιέχει τον πραγματικό πόρο. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Επιστρέφει το απόλυτο URI από τα βασικά και σχετικά URIs.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | java.lang.String | Βασικό URI των αντικειμένων σύνδεσης |
| relativeUri | java.lang.String | Σχετικό URI προς το συνδεδεμένο αντικείμενο. |

**Επιστροφή:**
java.lang.String - Απόλυτο URI ή null εάν το σχετικό URI δεν μπορεί να επιλυθεί.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Χαρτογραφεί ένα URI σε αντικείμενο που περιέχει τον πραγματικό πόρο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | java.lang.String | Απόλυτο URI προς το αντικείμενο. |

**Επιστροφή:**
java.io.InputStream - Ένα αντικείμενο InputStream ή null εάν δεν είναι δυνατή η ροή του πόρου.