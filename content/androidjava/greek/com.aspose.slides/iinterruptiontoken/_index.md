---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /el/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Αυτή η κλάση αντιπροσωπεύει το token που χρησιμοποιείται για την ένδειξη σε εργασίες μεγάλης διάρκειας εάν ζητήθηκε η διακοπή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Επιστρέφει true εάν ζητήθηκε διακοπή. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Ρίχνει μια εξαίρεση εάν ζητήθηκε διακοπή. |
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


Ρίχνει μια εξαίρεση εάν ζητήθηκε διακοπή.