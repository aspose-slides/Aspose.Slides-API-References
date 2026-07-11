---
title: LinkEmbedDecision
second_title: Aspose.Slides για Android μέσω Java API Reference
description: Καθορίζει πώς θα υποβληθεί το αντικείμενο σε επεξεργασία κατά την αποθήκευση.
type: docs
url: /el/com.aspose.slides/linkembeddecision/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Καθορίζει πώς θα υποβληθεί το αντικείμενο σε επεξεργασία κατά την αποθήκευση.
## Fields

| Field | Description |
| --- | --- |
| [Link](#Link) | Το αντικείμενο θα αποθηκευτεί εξωτερικά, με αναφορά μέσω URL |
| [Embed](#Embed) | Το αντικείμενο θα πρέπει να ενσωματωθεί σε ένα παραγόμενο αρχείο, εάν είναι δυνατόν. |
| [Ignore](#Ignore) | Το αντικείμενο θα παραβλεφθεί. |
### Σύνδεσμος {#Link}
```
public static final int Link
```


Το αντικείμενο θα αποθηκευτεί εξωτερικά, με αναφορά μέσω URL

### Ενσωμάτωση {#Embed}
```
public static final int Embed
```


Το αντικείμενο θα πρέπει να ενσωματωθεί σε ένα παραγόμενο αρχείο, εάν είναι δυνατόν. Εάν η ενσωμάτωση είναι αδύνατη, θα κληθεί η GetUrl και, ανάλογα με το αποτέλεσμα, το αντικείμενο θα αναφερθεί μέσω URL ή θα παραβλεφθεί.

### Παράβλεψη {#Ignore}
```
public static final int Ignore
```


Το αντικείμενο θα παραβλεφθεί.