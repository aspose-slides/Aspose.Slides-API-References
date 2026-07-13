---
title: ChartPortionFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Denna klass innehåller diagramdelens formateringsegenskaper som används i diagram.
type: docs
url: /sv/com.aspose.slides/chartportionformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

Denna klass innehåller diagramdelens formateringsegenskaper som används i diagram. Till skillnad från [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) är alla egenskaper i denna klass skrivbara.

--------------------

Denna klass används för att returnera och manipulera formateringsegenskaper för textdelar som definierats för den specifika delen. Detta innebär att ingen arv tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "undefined".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective)-metoden som returnerar en [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-instans.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long