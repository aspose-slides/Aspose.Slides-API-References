---
title: IWarningCallback
second_title: Aspose.Slides dla Androida poprzez interfejs API Java
description: Interfejs dla klas, które otrzymują ostrzeżenia
type: docs
url: /pl/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interfejs dla klas, które otrzymują ostrzeżenia
## Metody

| Metoda | Opis |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Metoda wywołania zwrotnego, która otrzymuje ostrzeżenie i decyduje, czy operacja powinna zostać przerwana. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Metoda wywołania zwrotnego, która otrzymuje ostrzeżenie i decyduje, czy operacja powinna zostać przerwana.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Ostrzeżenie do przetworzenia. |

**Zwraca:**
int - Decyzja o przerwaniu [ReturnAction](../../com.aspose.slides/returnaction).