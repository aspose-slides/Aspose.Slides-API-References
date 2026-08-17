---
title: HtmlExternalResolver
second_title: Αναφορά API του Aspose.Slides για Java
description: Αντικείμενο επανάκλησης που χρησιμοποιείται από τη ρουτίνα εισαγωγής HTML για την απόκτηση αναφερθέντων αντικειμένων όπως εικόνες.
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

Αντικείμενο επανάκλησης που χρησιμοποιείται από τη ρουτίνα εισαγωγής HTML για την απόκτηση αναφερθέντων αντικειμένων όπως εικόνες.

--------------------

Η χρήση αυτού του ανιχνευτή μπορεί να δημιουργήσει ένα κενό ασφαλείας όταν το παρεχόμενο από τον πελάτη αρχείο HTML επιτρέπει στο λογισμικό του διακομιστή να αποκτήσει τοπικό ή δικτυακό αρχείο. Χρησιμοποιήστε το με προσοχή. Συνιστάται να μην καθορίζετε καθόλου το HtmlExternalResolver (να διαβάζονται μόνο ενσωματωμένα αντικείμενα) ή να δημιουργήσετε κάποια υποκατηγορία που ελέγχει αν το καθορισμένο URI είναι έγκυρο.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Λύζει το απόλυτο URI από τις βασικές και σχετικές διευθύνσεις URI. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Λύζει το απόλυτο URI από τις βασικές και σχετικές διευθύνσεις URI.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | java.lang.String | Βασικό URI των αντικειμένων σύνδεσης |
| relativeUri | java.lang.String | Σχετικό URI προς το συνδεδεμένο αντικείμενο. |

**Επιστρέφει:**
java.lang.String - Απόλυτο URI ή null εάν το σχετικό URI δεν μπορεί να λυθεί.
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