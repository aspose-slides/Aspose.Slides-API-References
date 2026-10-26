---
title: ITabEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat de tabulatiestop-eigenschappen van effectieve teksten bevat.
type: docs
url: /nl/com.aspose.slides/itabeffectivedata/
---
**Alle geïmplementeerde interfaces:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

Onveranderlijk object dat de tabulatiestop-eigenschappen van effectieve tekst bevat.

--------------------

Deze interface wordt gebruikt als onderdeel van [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPosition()](#getPosition--) | Retourneert de positie van een tab. |
| [getAlignment()](#getAlignment--) | Retourneert de uitlijningsstijl van een tab. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```


Retourneert de positie van een tab. Het toewijzen van deze eigenschap kan de index van de tab in de collectie wijzigen en de Enumerator ongeldig maken. Alleen-lezen double.

**Returns:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Retourneert de uitlijningsstijl van een tab. Alleen-lezen [TabAlignment](../../com.aspose.slides/tabalignment).

**Returns:**
int