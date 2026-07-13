---
title: ITextStyleEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva textstilegenskaper.
type: docs
url: /sv/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Oföränderligt objekt som innehåller effektiva textstilegenskaper.

--------------------

Detta gränssnitt används tillsammans med [ITextStyle](../../com.aspose.slides/itextstyle)-gränssnittet för att returnera effektiva formateringsvärden med arv tillämpat.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Returnerar nivån på den effektiva stilen. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Returnerar effektiva standardparagrafegenskaper. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Returnerar nivån på den effektiva stilen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Nollbaserat index för nivån. Måste ligga i 0..8-intervallet. |

**Returnerar:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Effektiv formatering av nivå [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Returnerar effektiva standardparagrafegenskaper. Skrivskyddad [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Returnerar:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)