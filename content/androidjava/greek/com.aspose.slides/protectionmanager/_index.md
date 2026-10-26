---
title: ProtectionManager
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Διαχείριση προστασίας παρουσίασης με κωδικό.
type: docs
url: /el/com.aspose.slides/protectionmanager/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Διαχείριση προστασίας παρουσίασης με κωδικό.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό. |
| [isEncrypted()](#isEncrypted--) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι κρυπτογραφημένη. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. |
| [isWriteProtected()](#isWriteProtected--) | Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσίαση είναι προστατευμένη ενάντια στην εγγραφή. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό. |
| [removeEncryption()](#removeEncryption--) | Αφαιρεί την κρυπτογράφηση. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό. |
| [removeWriteProtection()](#removeWriteProtection--) | Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Καθορίζει αν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Επιστρέφει τον κωδικό που χρησιμοποιείται για την κρυπτογράφηση της παρουσίασης. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Επιστρέφει ή ορίζει σύσταση μόνο ανάγνωσης. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Επιστρέφει ή ορίζει σύσταση μόνο ανάγνωσης. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό. Εάν είναι true, τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Δυαδική μεταβλητή ανάγνωσης/εγγραφής.

**Επιστρέφει:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Αυτή η ιδιότητα έχει νόημα, εάν η παρουσίαση είναι προστατευμένη με κωδικό. Εάν είναι true, τότε οι ιδιότητες εγγράφου κρυπτογραφούνται στο αρχείο παρουσίασης. Εάν είναι false, τότε οι ιδιότητες εγγράφου είναι δημόσιες ενώ η παρουσίαση είναι κρυπτογραφημένη. Δυαδική μεταβλητή ανάγνωσης/εγγραφής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσία είναι κρυπτογραφημένη. Δυαδική μεταβλητή μόνο ανάγνωση.

Τιμή: true εάν η παρουσίαση φορτώθηκε από κρυπτογραφημένο αρχείο ή κλήθηκε η μέθοδος \#encrypt(String).encrypt(String)· διαφορετικά, false.

**Επιστρέφει:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Αυτή η ιδιότητα έχει νόημα, εάν το αρχείο παρουσίασης είναι προστατευμένο με κωδικό και οι ιδιότητες εγγράφου αυτού του αρχείου είναι δημόσιες. Η τιμή true σημαίνει ότι μόνο οι ιδιότητες εγγράφου φορτώνονται από κρυπτογραφημένο αρχείο παρουσίασης χωρίς χρήση κωδικού. Η τιμή false σημαίνει ότι φορτώνεται ολόκληρη η κρυπτογραφημένη παρουσίαση με χρήση του σωστού κωδικού, όχι μόνο οι ιδιότητες εγγράφου. Εάν η παρουσίαση δεν είναι κρυπτογραφημένη, τότε η τιμή της ιδιότητας είναι πάντα false. Εάν οι ιδιότητες εγγράφου ενός κρυπτογραφημένου αρχείου δεν είναι δημόσιες, τότε η τιμή της ιδιότητας είναι πάντα false. Εάν η Presentation.EncryptDocumentProperties είναι true, τότε η τιμή της IsOnlyDocumentPropertiesLoaded είναι πάντα false. Δυαδική μεταβλητή μόνο ανάγνωση.

**Επιστρέφει:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Επιστρέφει μια τιμή που υποδεικνύει αν αυτή η παρουσίαση είναι προστατευμένη ενάντια στην εγγραφή. Δυαδική μεταβλητή μόνο ανάγνωση.

**Επιστρέφει:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Κρυπτογραφεί την παρουσίαση με τον καθορισμένο κωδικό.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
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

Ορίζει προστασία εγγραφής για αυτήν την παρουσίαση με τον καθορισμένο κωδικό.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
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

Αφαιρεί την προστασία εγγραφής για αυτήν την παρουσίαση.

--------------------

> ```
> Αυτό το παράδειγμα κώδικα δείχνει πώς να αφαιρέσετε την προστασία εγγραφής από μια παρουσίαση PowerPoint.
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
| password | java.lang.String | Ο κωδικός για έλεγχο. |

1. Θα πρέπει να ελέγξετε την ιδιότητα (\#isWriteProtected.isWriteProtected) πριν καλέσετε αυτή τη μέθοδο. 2. Όταν ο κωδικός είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean - True εάν ο κωδικός είναι έγκυρος· διαφορετικά, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Επιστρέφει τον κωδικό που χρησιμοποιείται για την κρυπτογράφηση της παρουσίασης. Συμβολοσειρά μόνο ανάγνωση.

**Επιστρέφει:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Επιστρέφει ή ορίζει σύσταση μόνο ανάγνωσης. Δυαδική μεταβλητή ανάγνωσης/εγγραφής.

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

Επιστρέφει ή ορίζει σύσταση μόνο ανάγνωσης. Δυαδική μεταβλητή ανάγνωσης/εγγραφής.

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