---
title: HandleRepeatedSpaces
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Καθορίζει πώς τα επαναλαμβανόμενα κανονικά διαστήματα πρέπει να αντιμετωπίζονται κατά την εξαγωγή σε Markdown.
type: docs
url: /el/com.aspose.slides/handlerepeatedspaces/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Καθορίζει πώς τα επαναλαμβανόμενα κανονικά διαστήματα πρέπει να αντιμετωπίζονται κατά την εξαγωγή σε Markdown.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [None](#None) | Όλα τα διαστήματα διατηρούνται ως κανονικά διαστήματα χωρίς καμία αλλαγή. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Μετατρέπει ακολουθίες από δύο ή περισσότερα διαδοχικά κανονικά διαστήματα εναλλάσσοντας μεταξύ κανονικών διαστημάτων και μη-σπαστικών κενών (NBSP). |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Μετατρέπει ακολουθίες από δύο ή περισσότερα διαδοχικά κανονικά διαστήματα διατηρώντας το πρώτο διάστημα ως κανονικό και αντικαθιστώντας όλα τα επόμενα διαστήματα με μη-σπαστικά κενά (NBSP). |

### None {#None}
```
public static final int None
```

Όλα τα διαστήματα διατηρούνται ως κανονικά διαστήματα χωρίς καμία αλλαγή. Δεν εφαρμόζεται καμία μετατροπή, και τα πολλαπλά διαδοχικά διαστήματα εξάγονται όπως είναι.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Μετατρέπει ακολουθίες από δύο ή περισσότερα διαδοχικά κανονικά διαστήματα εναλλάσσοντας μεταξύ κανονικών διαστημάτων και μη-σπαστικών κενών (NBSP). Το πρώτο διάστημα διατηρείται πάντα ως κανονικό.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Μετατρέπει ακολουθίες από δύο ή περισσότερα διαδοχικά κανονικά διαστήματα διατηρώντας το πρώτο διάστημα ως κανονικό και αντικαθιστώντας όλα τα επόμενα διαστήματα με μη-σπαστικά κενά (NBSP).