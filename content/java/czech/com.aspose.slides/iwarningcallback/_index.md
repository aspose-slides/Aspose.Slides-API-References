---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Rozhraní pro třídy, které přijímají varování
type: docs
url: /cs/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Rozhraní pro třídy, které přijímají varování
## Metody

| Metoda | Popis |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Metoda zpětného volání, která přijímá varování a rozhoduje, zda má být operace přerušena. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


Metoda zpětného volání, která přijímá varování a rozhoduje, zda má být operace přerušena.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Varování ke zpracování. |

**Návratová hodnota:**
int - Rozhodnutí o přerušení [ReturnAction](../../com.aspose.slides/returnaction).