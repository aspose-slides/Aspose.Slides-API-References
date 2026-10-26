---
title: ITabEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som innehåller de effektiva tabbstoppsegenskaperna för texten.
type: docs
url: /sv/com.aspose.slides/itabeffectivedata/
---
**Alla implementerade gränssnitt:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Oföränderligt objekt som innehåller de effektiva tabbstoppsegenskaperna för texten.

--------------------

Detta gränssnitt används som en del av [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPosition()](#getPosition--) | Returnerar positionen för en tabulator. |
| [getAlignment()](#getAlignment--) | Returnerar justeringsstil för en tabulator. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

Returnerar positionen för en tabulator. Att tilldela denna egenskap kan förändra tabulatorns index i samlingen och ogiltigförklara Enumerator. Skrivskyddad double.

**Returnerar:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Returnerar justeringsstil för en tabulator. Skrivskyddad [TabAlignment](../../com.aspose.slides/tabalignment).

**Returnerar:**
int