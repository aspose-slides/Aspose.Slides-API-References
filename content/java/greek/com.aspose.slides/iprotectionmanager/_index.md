---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Διαχείριση προστασίας με κωδικό παρουσίασης.
type: docs
url: /el/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Διαχείριση προστασίας με κωδικό παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι προστατευμένη με κωδικό. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι προστατευμένη με κωδικό. |
| [isEncrypted()](#isEncrypted--) | Αποκτά μια τιμή που υποδεικνύει αν αυτή η υπόσταση είναι κρυπτογραφημένη. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό και οι ιδιότητες του εγγράφου αυτού του αρχείου είναι δημόσιες. |
| [isWriteProtected()](#isWriteProtected--) | Αποκτά μια τιμή που υποδεικνύει αν αυτή η παρουσίαση είναι προστατευμένη ενάντια στην εγγραφή. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Επιστρέφει τον κωδικό κρυπτογράφησης. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Αποκτά ή ορίζει συστάση μόνο για ανάγνωση. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Αποκτά ή ορίζει συστάση μόνο για ανάγνωση. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό. |
| [removeEncryption()](#removeEncryption--) | Αφαιρεί την κρυπτογράφηση. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό. |
| [removeWriteProtection()](#removeWriteProtection--) | Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Καθορίζει αν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι προστατευμένη με κωδικό. Εάν είναι true, τότε οι ιδιότητες του εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες του εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Δυαδική τιμή ανάγνωση/εγγραφή.

**Επιστρέφει:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Αυτή η ιδιότητα έχει νόημα εάν η παρουσίαση είναι προστατευμένη με κωδικό. Εάν είναι true, τότε οι ιδιότητες του εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες του εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Δυαδική τιμή ανάγνωση/εγγραφή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Αποκτά μια τιμή που υποδεικνύει αν αυτή η υπόσταση είναι κρυπτογραφημένη. Μόνο για ανάγνωση δυαδική τιμή.

Τιμή: true εάν η παρουσίαση φορτώθηκε από κρυπτογραφημένο αρχείο ή κλήθηκε η μέθοδος \#encrypt(String).encrypt(String)· διαφορετικά, false.

**Επιστρέφει:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Αυτή η ιδιότητα έχει νόημα εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό και οι ιδιότητες του εγγράφου αυτού του αρχείου είναι δημόσιες. Η τιμή true σημαίνει ότι μόνο οι ιδιότητες του εγγράφου φορτώνονται από ένα κρυπτογραφημένο αρχείο παρουσίασης χωρίς χρήση κωδικού. Η τιμή false σημαίνει ότι φορτώνεται ολόκληρη η κρυπτογραφημένη παρουσίαση με χρήση του σωστού κωδικού, όχι μόνο οι ιδιότητες του εγγράφου. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, η τιμή της ιδιότητας είναι πάντα false. Εάν οι ιδιότητες του εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, η τιμή της ιδιότητας είναι πάντα false. Εάν το PresentationEx.EncryptDocumentProperties είναι true, τότε η τιμή της IsOnlyDocumentPropertiesLoaded είναι πάντα false. Μόνο για ανάγνωση δυαδική τιμή.

**Επιστρέφει:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Αποκτά μια τιμή που υποδεικνύει αν αυτή η παρουσίαση είναι προστατευμένη ενάντια στην εγγραφή. Μόνο για ανάγνωση δυαδική τιμή.

**Επιστρέφει:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Επιστρέφει τον κωδικό κρυπτογράφησης. Μόνο για ανάγνωση String.

**Επιστρέφει:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Αποκτά ή ορίζει συστάση μόνο για ανάγνωση. Δυαδική τιμή ανάγνωση/εγγραφή.

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

Αποκτά ή ορίζει συστάση μόνο για ανάγνωση. Δυαδική τιμή ανάγνωση/εγγραφή.

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

Καθορίζει αν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση.

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
| password | java.lang.String | Ο κωδικός για έλεγχο.

1. Θα πρέπει να ελέγξετε την ιδιότητα (\#isWriteProtected.isWriteProtected) πριν καλέσετε αυτή τη μέθοδο. 2. Όταν ο κωδικός είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**  
boolean - True εάν ο κωδικός είναι έγκυρος· διαφορετικά, false.