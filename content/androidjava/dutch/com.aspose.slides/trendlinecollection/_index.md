---
title: TrendlineCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling Trendline voor
type: docs
url: /nl/com.aspose.slides/trendlinecollection/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Stelt een verzameling Trendline voor
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [add(int trendlineType)](#add-int-) | Voegt de nieuwe Trendline toe aan het einde van een collectie en retourneert deze. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Verwijdert de opgegeven waarde. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [getCount()](#getCount--) | Haalt het aantal werkelijk in de collectie aanwezige elementen op. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [Trendline](../../com.aspose.slides/trendline).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Voegt de nieuwe Trendline toe aan het einde van een collectie en retourneert deze.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| trendlineType | int |  |

**Retour:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Een java.util.Iterator voor de volledige collectie.
### getCount() {#getCount--}
```
public final int getCount()
```

Haalt het aantal werkelijk in de collectie aanwezige elementen op. Alleen-lezen int.

**Retour:**
int