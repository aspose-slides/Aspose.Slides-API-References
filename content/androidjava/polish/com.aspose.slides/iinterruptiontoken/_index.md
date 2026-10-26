---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /pl/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Ta klasa reprezentuje token używany do sygnalizowania długotrwałych zadań, czy przerwanie zostało żądane.
## Metody

| Method | Description |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Zwraca true, jeśli przerwanie zostało żądane. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Rzuca wyjątek, jeśli przerwanie zostało żądane. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Zwraca true, jeśli przerwanie zostało żądane.

**Zwraca:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Rzuca wyjątek, jeśli przerwanie zostało żądane.