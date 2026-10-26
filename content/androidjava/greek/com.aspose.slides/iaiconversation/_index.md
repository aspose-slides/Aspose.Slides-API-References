---
title: IAIConversation
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a conversation instance.
type: docs
url: /el/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

Αντιπροσωπεύει μια παρουσία συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν ολόκληρο το πλαίσιο.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | Αποστέλλει μήνυμα αίτησης συνομιλίας που περιλαμβάνει ολόκληρο το πλαίσιο και επιστρέφει την απάντηση. |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```


Αποστέλλει μήνυμα αίτησης συνομιλίας που περιλαμβάνει ολόκληρο το πλαίσιο και επιστρέφει την απάντηση.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η εντολή ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργείται από το μοντέλο AI ως απάντηση στην δοθείσα εντολή μέσα στο πλαίσιο της συνομιλίας.