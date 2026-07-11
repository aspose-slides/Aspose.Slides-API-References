---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Διαχείριση προστασίας κωδικού παρουσίασης.
type: docs
url: /el/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Διαχείριση προστασίας κωδικού παρουσίασης.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι προστατευμένη με κωδικό. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι προστατευμένη με κωδικό. |
| [isEncrypted()](#isEncrypted--) | Επιστρέφει μια τιμή που υποδηλώνει αν αυτή η παρουσία είναι κρυπτογραφημένη. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι κωδικοπροστατευμένο και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. |
| [isWriteProtected()](#isWriteProtected--) | Επιστρέφει μια τιμή που υποδηλώνει αν αυτή η παρουσίαση είναι προστατευμένη από εγγραφή. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Επιστρέφει τον κωδικό κρυπτογράφησης. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Ανακτά ή ορίζει σύσταση μόνο ανάγνωσης. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Ανακτά ή ορίζει σύσταση μόνο ανάγνωσης. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό. |
| [removeEncryption()](#removeEncryption--) | Αφαιρεί την κρυπτογράφηση. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό. |
| [removeWriteProtection()](#removeWriteProtection--) | Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Καθορίζει εάν μια παρουσίαση είναι κωδικοπροστατευμένη για τροποποίηση. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι κωδικοπροστατευμένη. Εάν είναι true, τότε οι ιδιότητες του εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες του εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Boolean ανάγνωσης/εγγραφής.

**Επιστρέφει:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι κωδικοπροστατευμένη. Εάν είναι true, τότε οι ιδιότητες του εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες του εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Boolean ανάγνωσης/εγγραφής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Επιστρέφει μια τιμή που υποδηλώνει αν αυτή η παρουσία είναι κρυπτογραφημένη. Boolean μόνο για ανάγνωση.

Τιμή: true εάν η παρουσίαση φορτώθηκε από κρυπτογραφημένο αρχείο ή κλήθηκε η μέθοδος \#encrypt(String).encrypt(String)· διαφορετικά, false.

**Επιστρέφει:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι κωδικοπροστατευμένο και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. Η τιμή true σημαίνει ότι μόνο οι ιδιότητες εγγράφου φορτώνονται από ένα κρυπτογραφημένο αρχείο παρουσίασης χωρίς χρήση κωδικού. Η τιμή false σημαίνει ότι φορτώνεται ολόκληρη η κρυπτογραφημένη παρουσίαση με χρήση του σωστού κωδικού, όχι μόνο οι ιδιότητες εγγράφου. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας είναι πάντα false. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, η τιμή της ιδιότητας είναι πάντα false. Εάν το PresentationEx.EncryptDocumentProperties είναι true, τότε η τιμή του IsOnlyDocumentPropertiesLoaded είναι πάντα false. Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Επιστρέφει μια τιμή που υποδηλώνει αν αυτή η παρουσίαση είναι προστατευμένη από εγγραφή. Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Επιστρέφει τον κωδικό κρυπτογράφησης. String μόνο για ανάγνωση.

**Επιστρέφει:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Ανακτά ή ορίζει σύσταση μόνο ανάγνωσης. Boolean ανάγνωσης/εγγραφής.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Επιστρέφει:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Ανακτά ή ορίζει σύσταση μόνο ανάγνωσης. Boolean ανάγνωσης/εγγραφής.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Ο κωδικός. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Αφαιρεί την κρυπτογράφηση.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | java.lang.String | Ο κωδικός. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Καθορίζει εάν μια παρουσίαση είναι κωδικοπροστατευμένη για τροποποίηση.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | java.lang.String | Ο κωδικός για έλεγχο. |

1. Θα πρέπει να ελέγξετε την ιδιότητα (\#isWriteProtected.isWriteProtected) πριν καλέσετε αυτή τη μέθοδο. 2. Όταν ο κωδικός είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean - True εάν ο κωδικός είναι έγκυρος· διαφορετικά, false.