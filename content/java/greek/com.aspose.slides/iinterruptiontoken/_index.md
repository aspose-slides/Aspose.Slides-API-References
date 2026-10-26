---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την ενημέρωση των μακροχρόνιων εργασιών εάν ζητήθηκε διακοπή.
type: docs
url: /el/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Αυτή η κλάση αντιπροσωπεύει το διακριτικό που χρησιμοποιείται για την ενημέρωση των μακροχρόνιων εργασιών εάν ζητήθηκε διακοπή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Επιστρέφει true εάν ζητήθηκε διακοπή. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Αποβάλλει αν ζητήθηκε διακοπή. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Επιστρέφει true εάν ζητήθηκε διακοπή.

**Επιστρέφει:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Αποβάλλει αν ζητήθηκε διακοπή.