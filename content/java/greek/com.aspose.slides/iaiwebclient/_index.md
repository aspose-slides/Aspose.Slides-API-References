---
title: IAIWebClient
second_title: Aspose.Slides for Java API Reference
description: Διεπαφή AI Web client.
type: docs
url: /el/com.aspose.slides/iaiwebclient/
---```
public interface IAIWebClient
```

Διεπαφή AI Web client. Αυτή η διεπαφή επιτρέπει την αντικατάσταση διαφορετικών μοντέλων γλώσσας AI. Οι κλάσεις που υλοποιούν αυτή τη διεπαφή προορίζονται να χρησιμοποιούνται μαζί με SlidesAIAgent.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [callChat(String instruction)](#callChat-java.lang.String-) | Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας ένα παρεχόμενο αντικείμενο HttpConnection και επιστρέφει το μήνυμα απάντησης στην δεδομένη εντολή. |
| [createConversation()](#createConversation--) | Δημιουργεί ένα στιγμιότυπο συνομιλίας. |
### callChat(String instruction) {#callChat-java.lang.String-}
```
public abstract String callChat(String instruction)
```

Στέλνει μια εντολή συνομιλίας στο μοντέλο AI χρησιμοποιώντας ένα παρεχόμενο αντικείμενο HttpConnection και επιστρέφει το μήνυμα απάντησης στην δεδομένη εντολή.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| instruction | java.lang.String | Η εντολή ή το μήνυμα που θα επεξεργαστεί το μοντέλο AI. |

**Επιστρέφει:**
java.lang.String - Το μήνυμα που δημιουργήθηκε από το μοντέλο AI ως απάντηση στην δεδομένη εντολή.
### createConversation() {#createConversation--}
```
public abstract IAIConversation createConversation()
```

Δημιουργεί ένα στιγμιότυπο συνομιλίας. Σε αντίθεση με τις κανονικές κλήσεις AI, οι συνομιλίες διατηρούν ολόκληρο το πλαίσιο.

**Επιστρέφει:**
[IAIConversation](../../com.aspose.slides/iaiconversation) - Ένα [IAIConversation](../../com.aspose.slides/iaiconversation) στιγμιότυπο.