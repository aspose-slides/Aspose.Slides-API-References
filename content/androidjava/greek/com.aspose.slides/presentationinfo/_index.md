---
title: PresentationInfo
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Πληροφορίες σχετικά με το αρχείο παρουσίασης
type: docs
url: /el/com.aspose.slides/presentationinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Πληροφορίες σχετικά με το αρχείο παρουσίασης
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Λαμβάνει True εάν η συνδεδεμένη παρουσίαση είναι κρυπτογραφημένη, διαφορετικά False. |
| [isPasswordProtected()](#isPasswordProtected--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για άνοιγμα. |
| [isWriteProtected()](#isWriteProtected--) | Λαμβάνει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη από εγγραφή. |
| [getLoadFormat()](#getLoadFormat--) | Λαμβάνει τη μορφή της συνδεδεμένης παρουσίασης. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για παρουσίαση που είναι προστατευμένη με κωδικό ανοίγματος. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ελέγχει εάν ο κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση που είναι προστατευμένη από εγγραφή. |
| [readDocumentProperties()](#readDocumentProperties--) | Λαμβάνει τις ιδιότητες εγγράφου της συνδεδεμένης παρουσίασης. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Γράφει τη συνδεδεμένη παρουσίαση σε ροή. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Γράφει τη συνδεδεμένη παρουσίαση σε αρχείο. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Λαμβάνει True εάν η συνδεδεμένη παρουσίαση είναι κρυπτογραφημένη, διαφορετικά False. Boolean μόνο για ανάγνωση.

**Επιστρέφει:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για άνοιγμα.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Επιστρέφει:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη από εγγραφή.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Εάν η παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για άνοιγμα, η τιμή της ιδιότητας είναι ίση με NotDefined.

**Επιστρέφει:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


Λαμβάνει τη μορφή της συνδεδεμένης παρουσίασης. Boolean μόνο για ανάγνωση [LoadFormat](../../com.aspose.slides/loadformat).

**Επιστρέφει:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```


Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για παρουσίαση που είναι προστατευμένη με κωδικό ανοίγματος.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | java.lang.String | Ο κωδικός πρόσβασης προς έλεγχο.

--------------------

Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean - True εάν η παρουσίαση είναι προστατευμένη με κωδικό ανοίγματος και ο κωδικός είναι σωστός, διαφορετικά false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Ελέγχει εάν ο κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση που είναι προστατευμένη από εγγραφή.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | java.lang.String | Ο κωδικός πρόσβασης προς έλεγχο.

--------------------

1. Πρέπει να ελέγξετε την (\#isWriteProtected.isWriteProtected) ιδιότητα πριν καλέσετε αυτή τη μέθοδο. 2. Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean - True εάν η παρουσίαση είναι προστατευμένη από εγγραφή και ο κωδικός είναι σωστός. False διαφορετικά.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```


Λαμβάνει τις ιδιότητες εγγράφου της συνδεδεμένης παρουσίασης.

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```


Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης.

--------------------

> ```
> Αυτό το παράδειγμα δείχνει πώς να καλέσετε τη μέθοδο #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) για
>  να ενημερώσετε τις ιδιότητες του εγγράφου που επιστρέφονται από την κλήση της μεθόδου #readDocumentProperties.readDocumentProperties.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```


Γράφει τη συνδεδεμένη παρουσίαση σε ροή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.OutputStream | Η ροή πρέπει να είναι επαναληπτική και εγγράψιμη.

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```


Γράφει τη συνδεδεμένη παρουσίαση σε αρχείο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο παρουσίασης. |