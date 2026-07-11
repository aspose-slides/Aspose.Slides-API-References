---
title: ICellCollection
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει μια συλλογή κελιών.
type: docs
url: /el/com.aspose.slides/icellcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Αντιπροσωπεύει μια συλλογή κελιών.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει ένα κελί με βάση τη θέση του. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Επιστρέφει ένα κελί με βάση τη θέση του. Μόνο για ανάγνωση [ICell](../../com.aspose.slides/icell).

--------------------

Ένα αντικείμενο CellEx μπορεί να επιστραφεί για πολλαπλούς δείκτες στην περίπτωση που το κελί είναι συγχωνευμένο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[ICell](../../com.aspose.slides/icell)