---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: Αναπαριστά ένα αντικείμενο συζήτησης.
type: docs
url: /el/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Αναπαριστά ένα αντικείμενο συζήτησης. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συζητήσεις διατηρούν ολόκληρο το συμφραζόμενο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Στέλνει το μήνυμα αιτήματος συζήτησης που περιλαμβάνει ολόκληρο το συμφραζόμενο και επιστρέφει την απόκριση. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

Στέλνει το μήνυμα αιτήματος συζήτησης που περιλαμβάνει ολόκληρο το συμφραζόμενο και επιστρέφει την απόκριση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η οδηγία ή το μήνυμα που θα υποβληθεί σε επεξεργασία από το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργήθηκε από το μοντέλο AI ως απάντηση στην δεδομένη οδηγία μέσα στο συμφραζόμενο της συζήτησης.