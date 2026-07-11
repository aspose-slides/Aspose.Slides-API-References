---
title: ISmartArtNodeCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αντιπροσωπεύει μια συλλογή κόμβων SmartArt.
type: docs
url: /el/com.aspose.slides/ismartartnodecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Αντιπροσωπεύει μια συλλογή κόμβων SmartArt.
## Μέθοδοι

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει τον κόμβο με βάση τον δείκτη. |
| [addNode()](#addNode--) | Προσθέτει νέο κόμβο ή υποκόμβο. |
| [removeNode(int index)](#removeNode-int-) | Αφαιρεί κόμβο ή υποκόμβο με βάση τον δείκτη. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Αφαιρεί κόμβο ή υποκόμβο. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Επιστρέφει τον κόμβο με βάση τον δείκτη. Μόνο για ανάγνωση [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου. |

**Τιμή επιστροφής:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Προσθέτει νέο κόμβο ή υποκόμβο.

**Τιμή επιστροφής:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Προστέθηκε κόμβος
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Αφαιρεί κόμβο ή υποκόμβο με βάση τον δείκτη.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Δείκτης μηδενικής βάσης του κόμβου |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Αφαιρεί κόμβο ή υποκόμβο.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Κόμβος προς αφαίρεση. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Προσθέτει νέο κόμβο στη επιλεγμένη θέση της συλλογής κόμβων.

**Παράμετροι:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Θέση κόμβου με μηδενική βάση. |

**Τιμή επιστροφής:**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Προστέθηκε κόμβος