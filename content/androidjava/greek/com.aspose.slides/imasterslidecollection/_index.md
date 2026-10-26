---
title: IMasterSlideCollection
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Αντιπροσωπεί μια συλλογή από κύριες διαφάνειες.
type: docs
url: /el/com.aspose.slides/imasterslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Αντιπροσωπεί μια συλλογή από κύριες διαφάνειες.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή. |
| [removeAt(int index)](#removeAt-int-) | Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Αφαιρεί τις αχρησιμοποίητες κύριες διαφάνειες. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Προσθέτει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στο τέλος της συλλογής. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Εισάγει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IMasterSlide](../../com.aspose.slides/imasterslide).

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

Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ο δείκτης μηδενικής βάσης του στοιχείου που θα αφαιρεθεί. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Αφαιρεί τις αχρησιμοποίητες κύριες διαφάνειες.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ignorePreserveField | boolean | Καθορίζει αν αυτή η μέθοδος πρέπει να αφαιρέσει τις αχρησιμοποίητες κύριες διαφάνειες ακόμη και αν η ιδιότητα [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) της έχει οριστεί σε true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Προσθέτει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στο τέλος της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια για κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Προστέθηκε διαφάνεια.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Εισάγει ένα αντίγραφο μιας συγκεκριμένης κύριας διαφάνειας στη συγκεκριμένη θέση της συλλογής. Οι συνδεδεμένες διαφάνειες διάταξης θα αντιγραφούν επίσης.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης της νέας διαφάνειας. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Διαφάνεια για κλωνοποίηση. |

**Επιστρέφει:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Εισήχθη κύρια διαφάνεια.