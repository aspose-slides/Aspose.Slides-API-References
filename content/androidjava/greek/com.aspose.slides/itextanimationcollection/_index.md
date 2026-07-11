---
title: ITextAnimationCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά μια συλλογή κειμενικών κινήσεων.
type: docs
url: /el/com.aspose.slides/itextanimationcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Αναπαριστά μια συλλογή κειμενικών κινήσεων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το στοιχείο κατά δείκτη. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Επιστρέφει όλα τα στοιχεία |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

Επιστρέφει το στοιχείο κατά δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

Επιστρέφει όλα τα στοιχεία

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) στοιχείο. |

**Επιστρέφει:**
com.aspose.slides.ITextAnimation[] - Πίνακας των [ITextAnimation](../../com.aspose.slides/itextanimation)