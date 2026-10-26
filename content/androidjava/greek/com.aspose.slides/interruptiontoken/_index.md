---
title: InterruptionToken
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την ένδειξη σε εργασίες μεγάλης διάρκειας εάν έχει ζητηθεί διακοπή.
type: docs
url: /el/com.aspose.slides/interruptiontoken/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την ένδειξη σε εργασίες μεγάλης διάρκειας εάν έχει ζητηθεί διακοπή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getNone()](#getNone--) | Αντιπροσωπεύει ένα κενό διακριτικό διακοπής. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Επιστρέφει true εάν έχει ζητηθεί διακοπή. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Ρίχνει μια εξαίρεση εάν έχει ζητηθεί διακοπή. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Αντιπροσωπεύει ένα κενό διακριτικό διακοπής.

--------------------

Οι λειτουργίες μεγάλης διάρκειας δεν θα διακοπούν ποτέ μέσω [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) όταν χρησιμοποιείται αυτό το διακριτικό.

**Επιστρέφει:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Επιστρέφει true εάν έχει ζητηθεί διακοπή.

**Επιστρέφει:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Ρίχνει μια εξαίρεση εάν έχει ζητηθεί διακοπή.