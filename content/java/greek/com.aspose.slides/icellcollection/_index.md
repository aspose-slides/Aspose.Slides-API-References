---
title: ICellCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αναπαριστά μια συλλογή από κελιά.
type: docs
url: /el/com.aspose.slides/icellcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Αναπαριστά μια συλλογή από κελιά.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα κελί με τη θέση του. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Επιστρέφει ένα κελί με τη θέση του. Μόνο για ανάγνωση [ICell](../../com.aspose.slides/icell).

--------------------

Ένα αντικείμενο CellEx μπορεί να επιστραφεί για πολλούς δείκτες σε περίπτωση που το κελί είναι συγχωνευμένο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICell](../../com.aspose.slides/icell)