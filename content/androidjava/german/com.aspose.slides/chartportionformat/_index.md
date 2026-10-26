---
title: ChartPortionFormat
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Diese Klasse enthält die Diagrammabschnitt-Formatierungseigenschaften, die in Diagrammen verwendet werden.
type: docs
url: /de/com.aspose.slides/chartportionformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

This class contains the chart portion formatting properties used in charts. Unlike [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

--------------------

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".

In order to get the effective formatting parameter values including inherited you need to use [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) method which returns a [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) instance.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Schreibgeschützt long.

**Rückgabe:**
long