---
title: InterruptionToken
second_title: Aspose.Sildes για PHP μέσω Java API Reference
description: 
type: docs

url: /el/aspose.slides/interruptiontoken/
---
## InterruptionToken κλάση

Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την ένδειξη σε μακροχρόνιες εργασίες εάν έχει ζητηθεί διακοπή.

### getNone {#getNone}

| Όνομα | Περιγραφή |
| --- | --- |
| getNone () | Αντιπροσωπεύει ένα κενό διακριτικό διακοπής. Οι μακροχρόνιες λειτουργίες δεν θα διακόπτονται ποτέ μέσω InterruptionTokenSource#interrupt όταν χρησιμοποιείται αυτό το διακριτικό. |

**Επιστρέφει:**
InterruptionToken


---

### isInterruptionRequested {#isInterruptionRequested}

| Όνομα | Περιγραφή |
| --- | --- |
| isInterruptionRequested () | Επιστρέφει true εάν έχει ζητηθεί διακοπή. |

**Επιστρέφει:**
boolean


---

### throwIfInterruptionRequested {#throwIfInterruptionRequested}

| Όνομα | Περιγραφή |
| --- | --- |
| throwIfInterruptionRequested () | Ρίχνει εάν έχει ζητηθεί διακοπή. |

**Επιστρέφει:**
void

**Εξαίρεση**

| Σφάλμα | Κατάσταση |
| --- | --- |
| OperationCanceledException | Αναβαίνει όταν έχει ζητηθεί διακοπή. |