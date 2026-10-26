---
title: ProtectionManager
second_title: Aspose.Slides για Java API Αναφορά
description: Διαχείριση προστασίας παρουσίασης με κωδικό.
type: docs
url: /el/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Διαχείριση προστασίας κωδικού παρουσίασης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσία προστατεύεται με κωδικό. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσία προστατεύεται με κωδικό. |
| [isEncrypted()](#isEncrypted--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κρυπτογραφημένη. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης προστατεύεται με κωδικό και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. |
| [isWriteProtected()](#isWriteProtected--) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι προστατευμένη από εγγραφή. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Κρυπτογραφεί την παρουσία με συγκεκριμένο κωδικό. |
| [removeEncryption()](#removeEncryption--) | Αφαιρεί την κρυπτογράφηση. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ορίζει προστασία από εγγραφή για αυτήν την παρουσία με συγκεκριμένο κωδικό. |
| [removeWriteProtection()](#removeWriteProtection--) | Αφαιρεί την προστασία από εγγραφή για αυτήν την παρουσία. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Καθορίζει εάν μια παρουσία είναι προστατευμένη με κωδικό για τροποποίηση. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Λαμβάνει τον κωδικό που χρησιμοποιείται για την κρυπτογράφηση της παρουσίασης. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Λαμβάνει ή ορίζει σύσταση μόνο για ανάγνωση. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Λαμβάνει ή ορίζει σύσταση μόνο για ανάγνωση. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Αυτή η ιδιότητα έχει νόημα, εάν η παρουσία προστατεύεται με κωδικό. Εάν true τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν false τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσία είναι κρυπτογραφημένη. Ανάγνωση/εγγραφή boolean.

**Επιστρέφει:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Αυτή η ιδιότητα έχει νόημα, εάν η παρουσία προστατεύεται με κωδικό. Εάν true τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν false τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσία είναι κρυπτογραφημένη. Ανάγνωση/εγγραφή boolean.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κρυπτογραφημένη. Μόνο ανάγνωση boolean.

Τιμή: true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Επιστρέφει:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης προστατεύεται με κωδικό και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. Η τιμή true σημαίνει ότι φορτώνονται μόνο οι ιδιότητες εγγράφου από ένα κρυπτογραφημένο αρχείο παρουσίασης χωρίς χρήση κωδικού. Η τιμή false σημαίνει ότι φορτώνεται ολόκληρη η κρυπτογραφημένη παρουσία με χρήση σωστού κωδικού, όχι μόνο οι ιδιότητες εγγράφου. Εάν η παρουσία δεν είναι κρυπτογραφημένη, η τιμή είναι πάντα false. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, η τιμή είναι πάντα false. Εάν Presentation.EncryptDocumentProperties είναι true, η τιμή IsOnlyDocumentPropertiesLoaded είναι πάντα false. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι προστατευμένη από εγγραφή. Μόνο ανάγνωση boolean.

**Επιστρέφει:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Κρυπτογραφεί την παρουσία με συγκεκριμένο κωδικό.

--------------------

> ```
> Το παρακάτω δείγμα κώδικα δείχνει πώς να κρυπτογραφήσετε μια παρουσία PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Ο κωδικός. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Αφαιρεί την κρυπτογράφηση.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Ορίζει προστασία από εγγραφή για αυτήν την παρουσία με συγκεκριμένο κωδικό.

--------------------

> ```
> Το παρακάτω δείγμα κώδικα δείχνει πώς να ορίσετε προστασία εγγραφής σε μια παρουσία.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | java.lang.String | Ο κωδικός. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Αφαιρεί την προστασία από εγγραφή για αυτήν την παρουσία.

--------------------

> ```
> Αυτό το δείγμα κώδικα δείχνει πώς να αφαιρέσετε την προστασία εγγραφής από μια παρουσία PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Καθορίζει εάν μια παρουσία είναι προστατευμένη με κωδικό για τροποποίηση.

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
boolean - True if the password is valid; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Λαμβάνει τον κωδικό που χρησιμοποιείται για την κρυπτογράφηση της παρουσίασης. Μόνο ανάγνωση String.

**Επιστρέφει:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Λαμβάνει ή ορίζει σύσταση μόνο για ανάγνωση. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Λαμβάνει ή ορίζει σύσταση μόνο για ανάγνωση. Ανάγνωση/εγγραφή boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |