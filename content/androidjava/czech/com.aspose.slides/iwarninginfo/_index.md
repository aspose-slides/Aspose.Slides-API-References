---
title: IWarningInfo
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Representuje základní rozhraní pro všechna varování.
type: docs
url: /cs/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Representuje základní rozhraní pro všechna varování.
## Metody

| Metoda | Popis |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Pokud receiver není null, ukončí varování pro určeného receiver a vyvolá výjimku AbortRequestedException, pokud receiver rozhodne operaci přerušit. |
| [getWarningType()](#getWarningType--) | Vrací typ varování. |
| [getDescription()](#getDescription--) | Vrací čitelný popis tohoto varování. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Pokud receiver není null, ukončí varování pro určeného receiver a vyvolá výjimku AbortRequestedException, pokud receiver rozhodne operaci přerušit.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objekt receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |
### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Vrací typ varování. Pouze pro čtení [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Návratová hodnota:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Vrací čitelný popis tohoto varování. Pouze pro čtení String.

**Návratová hodnota:**
java.lang.String