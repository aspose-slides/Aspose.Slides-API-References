---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /hu/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Egy alap interfészt képvisel az összes figyelmeztetéshez.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Ha a receiver nem null, befejezi a figyelmeztetést a megadott receivernek, és AbortRequestedException-t dob, ha a receiver úgy dönt, hogy megszakítja a műveletet. |
| [getWarningType()](#getWarningType--) | Visszaad egy figyelmeztetés típusát. |
| [getDescription()](#getDescription--) | Visszaad egy ember által olvasható leírást erről a figyelmeztetésről. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


Ha a receiver nem null, befejezi a figyelmeztetést a megadott receivernek, és AbortRequestedException-t dob, ha a receiver úgy dönt, hogy megszakítja a műveletet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver objektum [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```


Visszaad egy figyelmeztetés típusát. Csak olvasható [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Visszatér:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Visszaad egy ember által olvasható leírást erről a figyelmeztetésről. Csak olvasható String.

**Visszatér:**
java.lang.String