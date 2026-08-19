---
title: IPortionFormat
second_title: Aspose.Slides för Java API-referens
description: Denna klass innehåller formateringsegenskaper för textdelar.
type: docs
url: /sv/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Denna klass innehåller formateringsegenskaper för textdelar. Till skillnad från [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelar som definierats för den specifika delen. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierad".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [getEffective](../../com.aspose.slides/iportionformat\#getEffective)-metoden som returnerar en [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returnerar eller anger bokmärkesidentifierare. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returnerar eller anger bokmärkesidentifierare. |
| [getSmartTagClean()](#getSmartTagClean--) | Avgör om smarttaggen ska rensas. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Avgör om smarttaggen ska rensas. |
| [getEffective()](#getEffective--) | Hämtar effektiva formateringsdata för delen med ärftlighet tillämpad. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```


Returnerar eller anger bokmärkesidentifierare. Läs/skriv String.

**Returnerar:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```


Returnerar eller anger bokmärkesidentifierare. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```


Avgör om smarttaggen ska rensas. Ingen arv tillämpas. Läs/skriv boolean.

**Returnerar:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```


Avgör om smarttaggen ska rensas. Ingen arv tillämpas. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```


Hämtar effektiva formateringsdata för delen med ärftlighet tillämpad.

**Returnerar:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - En [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).