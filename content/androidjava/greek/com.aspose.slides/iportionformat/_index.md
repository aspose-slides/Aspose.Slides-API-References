---
title: IPortionFormat
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου.
type: docs
url: /el/com.aspose.slides/iportionformat/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Αυτή η κλάση περιέχει τις ιδιότητες μορφοποίησης τμήματος κειμένου. Σε αντίθεση με [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), όλες οι ιδιότητες αυτής της κλάσης είναι εγγράψιμες.

--------------------

Αυτή η κλάση χρησιμοποιείται για την επιστροφή και τη διαχείριση των ιδιοτήτων μορφοποίησης τμήματος κειμένου που ορίζονται για το συγκεκριμένο τμήμα. Αυτό σημαίνει ότι δεν εφαρμόζεται κληρονομικότητα κατά την ανάκτηση των τιμών, έτσι για την πλειονότητα των περιπτώσεων θα λάβετε τιμές που σημαίνουν "απροσδιόριστο".

Για να λάβετε τις αποτελεσματικές τιμές των παραμέτρων μορφοποίησης, συμπεριλαμβανομένων των κληρονομημένων, πρέπει να χρησιμοποιήσετε τη μέθοδο [getEffective](../../com.aspose.slides/iportionformat\#getEffective) η οποία επιστρέφει ένα αντικείμενο [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Επιστρέφει ή ορίζει το αναγνωριστικό σελιδοδείκτη. |
| [getSmartTagClean()](#getSmartTagClean--) | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. |
| [getEffective()](#getEffective--) | Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με εφαρμογή κληρονομικότητας. |

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

Καθορίζει εάν η έξυπνη ετικέτα πρέπει να καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Καθορίζει εάν η έξυπνη ετικέτα πρέπει να Καθαριστεί. Δεν εφαρμόζεται κληρονομικότητα. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης τμήματος με εφαρμογή κληρονομικότητας.

**Επιστρέφει:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - ένα [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).