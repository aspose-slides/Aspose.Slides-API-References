---
title: IDigitalSignatureCollection
second_title: Aspose.Slides για Android μέσω Java API
description: Αντιπροσωπεύει μια συλλογή ψηφιακών υπογραφών που είναι προσαρτημένες σε ένα έγγραφο.
type: docs
url: /el/com.aspose.slides/idigitalsignaturecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IDigitalSignatureCollection extends IGenericCollection<IDigitalSignature>
```

Αντιπροσωπεύει μια συλλογή ψηφιακών υπογραφών που είναι προσαρτημένες σε ένα έγγραφο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει την υπογραφή με βάση το ευρετήριο. |
| [add(IDigitalSignature digitalSignature)](#add-com.aspose.slides.IDigitalSignature-) | Προσθέτει την υπογραφή στο τέλος της συλλογής. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί την υπογραφή στο καθορισμένο ευρετήριο. |
| [clear()](#clear--) | Αφαιρεί όλες τις υπογραφές από τη συλλογή. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDigitalSignature get_Item(int index)
```

Επιστρέφει την υπογραφή με βάση το ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IDigitalSignature](../../com.aspose.slides/idigitalsignature)
### add(IDigitalSignature digitalSignature) {#add-com.aspose.slides.IDigitalSignature-}
```
public abstract void add(IDigitalSignature digitalSignature)
```

Προσθέτει την υπογραφή στο τέλος της συλλογής.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      signature.setComments("Aspose.Slides digital signing test.");
>      pres.getDigitalSignatures().add(signature);
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| digitalSignature | [IDigitalSignature](../../com.aspose.slides/idigitalsignature) | Υπογραφή προς προσθήκη. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί την υπογραφή στο καθορισμένο ευρετήριο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της υπογραφής που πρέπει να διαγραφεί. |

### clear() {#clear--}
```
public abstract void clear()
```

Αφαιρεί όλες τις υπογραφές από τη συλλογή.