---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: Diese Klasse stellt das Token dar, das zur Signalisierung langer laufender Aufgaben verwendet wird, um anzuzeigen, ob eine Unterbrechung angefordert wurde.
type: docs
url: /de/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Diese Klasse stellt das Token dar, das zur Signalisierung langer laufender Aufgaben verwendet wird, um anzuzeigen, ob eine Unterbrechung angefordert wurde.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Gibt true zurück, wenn die Unterbrechung angefordert wurde. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Wirft eine Ausnahme, wenn die Unterbrechung angefordert wurde. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Gibt true zurück, wenn die Unterbrechung angefordert wurde.

**Rückgabe:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Wirft eine Ausnahme, wenn die Unterbrechung angefordert wurde.