---
title: ISmartArtNodeCollection
second_title: Αναφορά API του Aspose.Slides για Java
description: Αναπαριστά μια συλλογή από κόμβους SmartArt.
type: docs
url: /el/com.aspose.slides/ismartartnodecollection/
---
**Όλες οι υλοποιημένες διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Αναπαριστά μια συλλογή από κόμβους SmartArt.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει κόμβο με δείκτη. |
| [addNode()](#addNode--) | Προσθέτει νέο κόμβο ή υποκόμβο. |
| [removeNode(int index)](#removeNode-int-) | Αφαιρεί κόμβο ή υποκόμβο με βάση το δείκτη. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Αφαιρεί κόμβο ή υποκόμβο. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```

Επιστρέφει κόμβο με δείκτη. Μόνο για ανάγνωση [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου. |

**Επιστροφή:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```

Προσθέτει νέο κόμβο ή υποκόμβο.

**Επιστροφή:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Κόμβος που προστέθηκε
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```

Αφαιρεί κόμβο ή υποκόμβο με βάση το δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Μηδενικός δείκτης του κόμβου |
### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```

Αφαιρεί κόμβο ή υποκόμβο.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Κόμβος για αφαίρεση. |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```

Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| position | int | Μηδενική θέση του κόμβου. |

**Επιστροφή:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Κόμβος που προστέθηκε