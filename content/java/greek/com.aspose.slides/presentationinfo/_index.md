---
title: PresentationInfo
second_title: Aspose.Slides για Java API Αναφορά
description: Πληροφορίες για το αρχείο παρουσίασης
type: docs
url: /el/com.aspose.slides/presentationinfo/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Πληροφορίες για το αρχείο παρουσίασης
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Επιστρέφει True εάν η συνδεδεμένη παρουσίαση είναι κρυπτογραφημένη, διαφορετικά False. |
| [isPasswordProtected()](#isPasswordProtected--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση προστατεύεται με κωδικό πρόσβασης για άνοιγμα. |
| [isWriteProtected()](#isWriteProtected--) | Επιστρέφει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη κατά την εγγραφή. |
| [getLoadFormat()](#getLoadFormat--) | Επιστρέφει τη μορφή της συνδεδεμένης παρουσίασης. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση προστατευμένη με κωδικό ανοίγματος. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση προστατευμένη κατά την εγγραφή. |
| [readDocumentProperties()](#readDocumentProperties--) | Επιστρέφει τις ιδιότητες του εγγράφου της συνδεδεμένης παρουσίασης. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Γράφει τη συνδεδεμένη παρουσίαση σε ροή. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Γράφει τη συνδεδεμένη παρουσίαση σε αρχείο. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Επιστρέφει True εάν η συνδεδεμένη παρουσίαση είναι κρυπτογραφημένη, διαφορετικά False. Μόνο για ανάγνωση boolean.

**Επιστρέφει:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Επιστρέφει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση προστατεύεται με κωδικό πρόσβασης για άνοιγμα.

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

Επιστρέφει μια τιμή που υποδεικνύει εάν η συνδεδεμένη παρουσίαση είναι προστατευμένη κατά την εγγραφή.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Εάν η παρουσίαση προστατεύεται με κωδικό πρόσβασης για άνοιγμα, η τιμή της ιδιότητας ισούται με NotDefined.

**Επιστρέφει:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Επιστρέφει τη μορφή της συνδεδεμένης παρουσίασης. Μόνο για ανάγνωση [LoadFormat](../../com.aspose.slides/loadformat).

**Επιστρέφει:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση προστατευμένη με κωδικό ανοίγματος.

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | java.lang.String | Ο κωδικός πρόσβασης προς έλεγχο. |

--------------------

Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean - True εάν η παρουσίαση προστατεύεται με κωδικό ανοίγματος και ο κωδικός είναι σωστός και false διαφορετικά.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση προστατευμένη κατά την εγγραφή.

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
| password | java.lang.String | Ο κωδικός πρόσβασης προς έλεγχο. |

--------------------

1. Θα πρέπει να ελέγξετε την ιδιότητα (\#isWriteProtected.isWriteProtected) πριν καλέσετε αυτή τη μέθοδο. 2. Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. |

**Επιστρέφει:**
boolean - True εάν η παρουσίαση είναι προστατευμένη κατά την εγγραφή και ο κωδικός είναι σωστός. False διαφορετικά.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Επιστρέφει τις ιδιότητες του εγγράφου της συνδεδεμένης παρουσίασης.

**Επιστρέφει:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Ενημερώνει τις ιδιότητες της συνδεδεμένης παρουσίασης.

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
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
| stream | java.io.OutputStream | Η ροή πρέπει να είναι προσπελάσιμη και εγγράψιμη. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Γράφει τη συνδεδεμένη παρουσίαση σε αρχείο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | java.lang.String | Αρχείο παρουσίασης. |