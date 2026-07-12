---
title: IRevealTransition
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Megjeleníti a diaátmeneti effektust.
type: docs
url: /hu/com.aspose.slides/irevealtransition/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
```
public interface IRevealTransition extends ITransitionValueBase
```

Megjeleníti a diaátmeneti effektust.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Direction of transition. |
| [setDirection(int value)](#setDirection-int-) | Direction of transition. |
| [getThroughBlack()](#getThroughBlack--) | Specifies whether the transition fades through black. |
| [setThroughBlack(boolean value)](#setThroughBlack-boolean-) | Specifies whether the transition fades through black. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

Az átmenet iránya. Olvasás/írás [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

Az átmenet iránya. Olvasás/írás [TransitionLeftRightDirectionType](../../com.aspose.slides/transitionleftrightdirectiontype).

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getThroughBlack() {#getThroughBlack--}
```
public abstract boolean getThroughBlack()
```

Megadja, hogy az átmenet feketen keresztül halványul-e. Olvasás/írás boolean.

**Returns:**
boolean
### setThroughBlack(boolean value) {#setThroughBlack-boolean-}
```
public abstract void setThroughBlack(boolean value)
```

Megadja, hogy az átmenet feketen keresztül halványul-e. Olvasás/írás boolean.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |