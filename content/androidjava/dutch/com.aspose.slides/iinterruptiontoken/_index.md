---
title: IInterruptionToken
second_title: Aspose.Slides voor Android via Java API-referentie
description: Deze klasse vertegenwoordigt het token dat wordt gebruikt om lange taken te signaleren of de onderbreking is aangevraagd.
type: docs
url: /nl/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Deze klasse vertegenwoordigt het token dat wordt gebruikt om lange taken te signaleren of de onderbreking is aangevraagd.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Retourneert true als onderbreking is aangevraagd. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Gooit een fout als onderbreking is aangevraagd. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Retourneert true als onderbreking is aangevraagd.

**Retour:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Gooit een fout als onderbreking is aangevraagd.