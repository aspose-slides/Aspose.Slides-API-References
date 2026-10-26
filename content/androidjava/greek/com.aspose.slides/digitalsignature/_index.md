---
title: DigitalSignature
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Ψηφιακή υπογραφή σε υπογεγραμμένο αρχείο.
type: docs
url: /el/com.aspose.slides/digitalsignature/
---
**Κληρονόμηση:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

Ψηφιακή υπογραφή σε υπογεγραμμένο αρχείο.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // Αρχικοποίηση παρουσίασης
>  Presentation pres = new Presentation();
>  try {
>     // Δημιουργία αντικειμένου DigitalSignature με αρχείο PFX και κωδικό PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // Σχόλιο για τη νέα ψηφιακή υπογραφή
>      signature.setComments("Aspose.Slides digital signing test.");
>      // Προσθήκη ψηφιακής υπογραφής στην παρουσίαση
>      pres.getDigitalSignatures().add(signature);
>      // Αποθήκευση παρουσίασης
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // Αρχικοποίηση παρουσίασης
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // Έλεγχος εάν όλες οι ψηφιακές υπογραφές είναι έγκυρες
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο πιστοποιητικό. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο μονοπάτι αρχείου πιστοποιητικού και κωδικό πρόσβασης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCertificate()](#getCertificate--) | Αντικείμενο πιστοποιητικού που χρησιμοποιήθηκε για την υπογραφή του εγγράφου. |
| [isValid()](#isValid--) | Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει αλλοιωθεί, αυτή η τιμή θα είναι true. |
| [getSignTime()](#getSignTime--) | Η ώρα που υπογράφηκε το έγγραφο. |
| [getComments()](#getComments--) | Ο σκοπός της υπογραφής. |
| [setComments(String value)](#setComments-java.lang.String-) | Ο σκοπός της υπογραφής. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο πιστοποιητικό.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| certData | byte[] | μια σειρά byte που περιέχει το πιστοποιητικό |
| password | java.lang.String | Κωδικός πρόσβασης απαιτείται για την πρόσβαση στο πιστοποιητικό. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


Δημιουργεί ένα νέο αντικείμενο DigitalSignature με το καθορισμένο μονοπάτι αρχείου πιστοποιητικού και κωδικό πρόσβασης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Διαδρομή προς το αρχείο με το πιστοποιητικό. |
| password | java.lang.String | Κωδικός πρόσβασης απαιτείται για την πρόσβαση στο πιστοποιητικό. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


Αντικείμενο πιστοποιητικού που χρησιμοποιήθηκε για την υπογραφή του εγγράφου. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει αλλοιωθεί, αυτή η τιμή θα είναι true. Μόνο για ανάγνωση boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Η ώρα που υπογράφηκε το έγγραφο. Μόνο για ανάγνωση java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


Ο σκοπός της υπογραφής. Αναγνώσιμη/εγγράψιμη String.

**Επιστρέφει:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Ο σκοπός της υπογραφής. Αναγνώσιμη/εγγράψιμη String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |