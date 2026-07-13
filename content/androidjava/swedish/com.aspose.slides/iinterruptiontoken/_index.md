---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: Den här klassen representerar tokenet som används för att signalera långa uppgifter om ett avbrott har begärts.
type: docs
url: /sv/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Den här klassen representerar tokenet som används för att signalera långa uppgifter om ett avbrott har begärts.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returnerar true om avbrott begärdes. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kastar ett undantag om avbrott begärdes. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Returnerar true om avbrott begärdes.

**Returnerar:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Kastar ett undantag om avbrott begärdes.