---
title: HandleRepeatedSpaces
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει πώς πρέπει να αντιμετωπίζονται τα επαναλαμβανόμενα κανονικά κενά κατά την εξαγωγή σε Markdown.
type: docs
weight: 937
url: /el/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

Specifies how repeated regular space characters should be handled during Markdown export.

```cpp
enum class HandleRepeatedSpaces
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 | Όλα τα κενά διατηρούνται ως κανονικοί χαρακτήρες κενού χωρίς καμία αλλαγή. Δεν εφαρμόζεται καμία μετατροπή και πολλαπλά διαδοχικά κενά εξάγονται όπως είναι. |
| AlternateSpacesToNbsp | 1 | Μετατρέπει ακολουθίες δύο ή περισσότερων διαδοχικών κανονικών κενών εναλλάσσοντας μεταξύ κανονικών χαρακτήρων κενού και οντοτήτων μη-διασπαστών κενών (**&nbsp;**). Το πρώτο κενό διατηρείται πάντα ως κανονικό κενό. |
| MultipleSpacesToNbsp | 2 | Μετατρέπει ακολουθίες δύο ή περισσότερων διαδοχικών κανονικών κενών διατηρώντας το πρώτο κενό ως κανονικό χαρακτήρα κενού και αντικαθιστώντας όλα τα επόμενα κενά με οντότητες μη-διασπαστών κενών (**&nbsp;**). |

## Δείτε επίσης

* Περιοχή ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)