---
title: IWarningCallback
second_title: Aspose.Slides Java API-referencia
description: Azoknak az osztályoknak a felülete, amelyek figyelmeztetést kapnak
type: docs
url: /hu/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Azoknak az osztályoknak a felülete, amelyek figyelmeztetést kapnak
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Visszahívási metódus, amely figyelmeztetést kap, és eldönti, hogy a műveletet meg kell-e szakítani. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Visszahívási metódus, amely figyelmeztetést kap, és eldönti, hogy a műveletet meg kell-e szakítani.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | A feldolgozandó figyelmeztetés. |

**Visszatérési érték:**
int - Megszakítási döntés [ReturnAction](../../com.aspose.slides/returnaction).