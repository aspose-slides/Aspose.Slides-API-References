---
title: IMasterSlideCollection
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει μια συλλογή κύριων διαφανειών.
type: docs
url: /el/com.aspose.slides/imasterslidecollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Represents a collection of master slides.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Παίρνει το στοιχείο στο καθορισμένο δείκτη. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Εισάγει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας σε καθορισμένη θέση της συλλογής. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Παίρνει το στοιχείο στο καθορισμένο δείκτη. Μόνο για ανάγνωση [IMasterSlide](../../com.aspose.slides/imasterslide).

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int |  |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Η κύρια διαφάνεια προς αφαίρεση από τη συλλογή. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Αφαιρεί το στοιχείο στο καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο μηδενικός δείκτης του στοιχείου προς αφαίρεση. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Αφαιρεί αχρησιμοποίητες κύριες διαφάνειες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ignorePreserveField | boolean | Καθορίζει εάν αυτή η μέθοδος πρέπει να αφαιρέσει αχρησιμοποίητες κύριες διαφάνειες ακόμη και αν η ιδιότητα [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) της είναι ορισμένη σε true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Προσθέτει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας στο τέλος της συλλογής. Τα συνδεδεμένα διαφάνειες διάταξης θα αντιγραφούν επίσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια προς κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Πρόσθετη διαφάνεια.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Εισάγει ένα αντίγραφο μιας καθορισμένης κύριας διαφάνειας σε καθορισμένη θέση της συλλογής. Τα συνδεδεμένα διαφάνειες διάταξης θα αντιγραφούν επίσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια προς κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Εισαχθείσα κύρια διαφάνεια.