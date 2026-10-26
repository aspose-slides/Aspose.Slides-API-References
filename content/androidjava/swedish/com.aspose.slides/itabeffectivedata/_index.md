---
title: ITabEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller effektiva texters tabbstoppsegenskaper.
type: docs
url: /sv/com.aspose.slides/itabeffectivedata/
---
**All Implemented Interfaces:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Oföränderligt objekt som innehåller egenskaper för effektiva textens tabbstopp.

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


Returnerar positionen för en tabulator. Att tilldela denna egenskap kan ändra tabulatorns index i samlingen och ogiltigförklara Enumerator. Endast läs double.

**Returnerar:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Returnerar justeringsstil för en tabulator. Endast läs [TabAlignment](../../com.aspose.slides/tabalignment).

**Returnerar:**
int