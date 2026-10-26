---
title: Tab
second_title: Aspose.Slides för Java API-referens
description: Representerar en tabulering för en text.
type: docs
url: /sv/com.aspose.slides/tab/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Representerar en tabulering för en text.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Skapar ny Tab |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Returnerar eller anger positionen för en flik. |
| [setPosition(double value)](#setPosition-double-) | Returnerar eller anger positionen för en flik. |
| [getAlignment()](#getAlignment--) | Returnerar eller anger justeringsstil för en flik. |
| [setAlignment(int value)](#setAlignment-int-) | Returnerar eller anger justeringsstil för en flik. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Jämför den aktuella instansen med ett annat objekt av samma typ. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Skapar ny Tab

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | double | Tab-position. |
| align | int | Justering. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Returnerar eller anger positionen för en flik. Att tilldela denna egenskap kan ändra flikens index i samlingen och ogiltigförklara Enumerator. Läs/skriv double.

**Returnerar:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Returnerar eller anger positionen för en flik. Att tilldela denna egenskap kan ändra flikens index i samlingen och ogiltigförklara Enumerator. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Returnerar eller anger justeringsstil för en flik. Läs/skriv [TabAlignment](../../com.aspose.slides/tabalignment).

**Returnerar:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Returnerar eller anger justeringsstil för en flik. Läs/skriv [TabAlignment](../../com.aspose.slides/tabalignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Jämför den aktuella instansen med ett annat objekt av samma typ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Ett objekt att jämföra med denna instans. |

**Returnerar:**
int - En 32-bits heltal som indikerar den relativa ordningen för jämförelseobjekten. Returvärdet har följande betydelser: 

 * < 0 - Denna instans är mindre än obj.
 * = 0 - Denna instans är lika med obj.
 * > 0 - Denna instans är större än obj.