---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: Represents the source of .
type: docs
url: /el/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Αντιπροσωπεύει την πηγή του [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getToken()](#getToken--) | Επιστρέφει νέο token δεσμευμένο σε αυτό το [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource). |
| [isInterruptionRequested()](#isInterruptionRequested--) | Επιστρέφει true εάν ζητηθεί διακοπή, αλλιώς false. |
| [interrupt()](#interrupt--) | Αρχικοποιεί αίτημα για διακοπή. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


Επιστρέφει νέο token δεσμευμένο σε αυτό το [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Επιστρέφει:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Επιστρέφει true εάν ζητηθεί διακοπή, αλλιώς false.

**Επιστρέφει:**  
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


Αρχικοποιεί αίτημα για διακοπή.