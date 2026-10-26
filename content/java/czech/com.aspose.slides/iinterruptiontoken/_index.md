---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /cs/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Tato třída představuje token, který se používá k signalizaci dlouho běžících úloh, zda bylo požadováno přerušení.
## Metody

| Metoda | Popis |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Vrací true, pokud bylo požadováno přerušení. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Vyhodí výjimku, pokud bylo požadováno přerušení. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Vrací true, pokud bylo požadováno přerušení.

**Návratová hodnota:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Vyhodí výjimku, pokud bylo požadováno přerušení.