---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Ψηφιακή υπογραφή σε υπογραμμένο αρχείο.
type: docs
url: /el/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

Ψηφιακή υπογραφή σε υπογραμμένο αρχείο.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCertificate()](#getCertificate--) | Αντικείμενο πιστοποιητικού που χρησιμοποιήθηκε για την υπογραφή του εγγράφου. |
| [isValid()](#isValid--) | Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει τροποποιηθεί, αυτή η τιμή θα είναι true. |
| [getSignTime()](#getSignTime--) | Ο χρόνος που υπογράφηκε το έγγραφο. |
| [getComments()](#getComments--) | Ο σκοπός της υπογραφής. |
| [setComments(String value)](#setComments-java.lang.String-) | Ο σκοπός της υπογραφής. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

Αντικείμενο πιστοποιητικού που χρησιμοποιήθηκε για την υπογραφή του εγγράφου. Μόνο για ανάγνωση byte[].

**Επιστρέφει:**
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

Εάν αυτή η ψηφιακή υπογραφή είναι έγκυρη και το έγγραφο δεν έχει τροποποιηθεί, αυτή η τιμή θα είναι true. Μόνο για ανάγνωση boolean.

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
public abstract Date getSignTime()
```

Ο χρόνος που υπογράφηκε το έγγραφο. Μόνο για ανάγνωση java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Επιστρέφει:**
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

Ο σκοπός της υπογραφής. Ανάγνωση/Εγγραφή String.

**Επιστρέφει:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Ο σκοπός της υπογραφής. Ανάγνωση/Εγγραφή String.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String |  |