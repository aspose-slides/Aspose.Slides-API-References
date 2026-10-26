---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: A figyelmeztetést kapó osztályok interfésze
type: docs
url: /hu/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

A figyelmeztetést kapó osztályok interfésze
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Visszahívási metódus, amely figyelmeztetést kap, és eldönti, hogy a műveletet megszakítani kell-e. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Visszahívási metódus, amely figyelmeztetést kap, és eldönti, hogy a műveletet megszakítani kell-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | A feldolgozandó figyelmeztetés. |

**Visszatérési érték:**
int - Megszakítási döntés [ReturnAction](../../com.aspose.slides/returnaction).