---
title: IPortionFormat
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου.
type: docs
url: /el/com.aspose.slides/iportionformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι επεγγράψιμες.

--------------------

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά την λήψη των τιμών, οπότε στις περισσότερες περιπτώσεις θα λάβετε τιμές που σημαίνουν "απροσδιόριστο".

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [getEffective](../../com.aspose.slides/iportionformat\#getEffective) η οποία επιστρέφει ένα αντικείμενο [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. |
| [getSmartTagClean()](#getSmartTagClean--) | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμογή κληρονομικότητας. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String.

**Επιστρέφει:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. Ανάγνωση/εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Καθορίζει αν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με την εφαρμογή κληρονομικότητας.

**Επιστρέφει:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Ένα [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).