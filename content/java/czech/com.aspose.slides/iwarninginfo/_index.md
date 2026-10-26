---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje základní rozhraní pro všechna varování.
type: docs
url: /cs/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Reprezentuje základní rozhraní pro všechna varování.
## Metody

| Metoda | Popis |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Pokud není receiver null, ukončí varování pro zadaného receiver a vyhodí výjimku AbortRequestedException, pokud se receiver rozhodl operaci přerušit. |
| [getWarningType()](#getWarningType--) | Vrací typ varování. |
| [getDescription()](#getDescription--) | Vrací čitelný popis tohoto varování. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Pokud není receiver null, ukončí varování pro zadaného receiver a vyhodí výjimku AbortRequestedException, pokud se receiver rozhodl operaci přerušit.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objekt receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Vrací typ varování. Pouze pro čtení [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Vrací:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Vrací čitelný popis tohoto varování. Pouze pro čtení String.

**Vrací:**
java.lang.String