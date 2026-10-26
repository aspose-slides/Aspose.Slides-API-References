---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android μέσω αναφοράς API Java
description: Αντιπροσωπεύει την πηγή του.
type: docs
url: /el/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Αντιπροσωπεύει την πηγή του [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getToken()](#getToken--) | Returns new token binded to this [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returns true if interruption requested, false otherwise. |
| [interrupt()](#interrupt--) | Intialize request for interruption. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Επιστρέφει νέο token δεσμευμένο σε αυτό [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Επιστρέφει:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Επιστρέφει true εάν έχει ζητηθεί διακοπή, false διαφορετικά.

**Επιστρέφει:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Αρχικοποιεί την αίτηση για διακοπή.