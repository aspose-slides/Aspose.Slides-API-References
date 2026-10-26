---
title: InterruptionToken
second_title: Αναφορά API του Aspose.Slides για Java
description: Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την επισήμανση μακροχρόνιων εργασιών εάν ζητήθηκε η διακοπή.
type: docs
url: /el/com.aspose.slides/interruptiontoken/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διασυνδέσεις:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την επισήμανση μακροχρόνιων εργασιών εάν ζητήθηκε η διακοπή.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getNone()](#getNone--) | Αντιπροσωπεύει ένα κενό διακριτικό διακοπής. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Επιστρέφει true αν ζητήθηκε η διακοπή. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Καλεί μια εξαίρεση αν ζητήθηκε η διακοπή. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Αντιπροσωπεύει ένα κενό διακριτικό διακοπής.

--------------------

Οι λειτουργίες μακράς διάρκειας δεν θα διακοπούν ποτέ μέσω [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) όταν χρησιμοποιείται αυτό το διακριτικό.

**Επιστρέφει:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Επιστρέφει true αν ζητήθηκε η διακοπή.

**Επιστρέφει:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Καλεί μια εξαίρεση αν ζητήθηκε η διακοπή.