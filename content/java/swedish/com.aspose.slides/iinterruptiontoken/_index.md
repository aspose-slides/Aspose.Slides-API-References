---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /sv/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Denna klass representerar token som används för att signalera långa körande uppgifter om avbrottet har begärts.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Returnerar true om avbrottet har begärts. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kastar ett undantag om avbrottet har begärts. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Returnerar true om avbrottet har begärts.

**Returnerar:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Kastar ett undantag om avbrottet har begärts.