---
title: IWarningCallback
second_title: Aspose.Slides för Android via Java API-referens
description: Interface för klasser som tar emot varning
type: docs
url: /sv/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interface för klasser som tar emot varning
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Återuppringningsmetod som tar emot varning och beslutar om operationen ska avbrytas. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Återuppringningsmetod som tar emot varning och beslutar om operationen ska avbrytas.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Varning att behandla. |

**Returnerar:**
int - Avbrottsbeslut [ReturnAction](../../com.aspose.slides/returnaction).