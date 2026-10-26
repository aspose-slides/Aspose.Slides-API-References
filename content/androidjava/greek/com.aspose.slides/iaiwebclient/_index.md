---
title: IAIWebClient
second_title: Aspose.Slides για Android μέσω αναφοράς API Java
description: Διεπαφή πελάτη AI Web.
type: docs
url: /el/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Διεπαφή πελάτη AI Web. Αυτή η διεπαφή επιτρέπει την αντικατάσταση διαφορετικών μοντέλων γλώσσας AI. Οι κλάσεις που υλοποιούν αυτή τη διεπαφή προορίζονται να χρησιμοποιούνται μαζί με το SlidesAIAgent.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας ένα παρεχόμενο αντικείμενο HttpConnection και επιστρέφει το μήνυμα απάντησης στην δοσμένη εντολή. |
| [createConversation()](#createConversation--) | Δημιουργεί μια περίπτωση συζήτησης. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας ένα παρεχόμενο αντικείμενο HttpConnection και επιστρέφει το μήνυμα απάντησης στην δοσμένη εντολή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η εντολή ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργείται από το μοντέλο AI ως απάντηση στην δοσμένη εντολή.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Δημιουργεί μια περίπτωση συζήτησης. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συζητήσεις διατηρούν όλο το συμφραζόμενο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Μία [IAIConversation](../../com.aspose.slides/iaiconversation) περίπτωση.