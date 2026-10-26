---
title: LinkEmbedDecision
second_title: Aspose.Slides για Java – Αναφορά API
description: Καθορίζει πώς θα επεξεργαστεί το αντικείμενο κατά την αποθήκευση.
type: docs
url: /el/com.aspose.slides/linkembeddecision/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Καθορίζει πώς θα επεξεργαστεί το αντικείμενο κατά την αποθήκευση.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Link](#Link) | Το αντικείμενο θα αποθηκευτεί εξωτερικά, αναφερόμενο μέσω URL |
| [Embed](#Embed) | Το αντικείμενο θα πρέπει να ενσωματωθεί σε ένα παραγόμενο αρχείο εφόσον είναι δυνατόν. |
| [Ignore](#Ignore) | Το αντικείμενο θα αγνοηθεί. |
### Σύνδεσμος {#Link}
```
public static final int Link
```

Το αντικείμενο θα αποθηκευτεί εξωτερικά, αναφερόμενο μέσω URL

### Ενσωμάτωση {#Embed}
```
public static final int Embed
```

Το αντικείμενο θα πρέπει να ενσωματωθεί σε ένα παραγόμενο αρχείο εφόσον είναι δυνατόν. Εάν η ενσωμάτωση είναι αδύνατη, θα κληθεί το GetUrl και, ανάλογα με το αποτέλεσμα, το αντικείμενο θα αναφερθεί μέσω URL ή θα αγνοηθεί.

### Παράλειψη {#Ignore}
```
public static final int Ignore
```

Το αντικείμενο θα αγνοηθεί.