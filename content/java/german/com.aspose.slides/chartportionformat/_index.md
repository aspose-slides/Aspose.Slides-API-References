---
title: ChartPortionFormat
second_title: Aspose.Slides für Java API-Referenz
description: Diese Klasse enthält die Diagramm-Abschnittsformatierungseigenschaften, die in Diagrammen verwendet werden.
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

Diese Klasse enthält die Diagramm-Abschnittsformatierungseigenschaften, die in Diagrammen verwendet werden. Im Gegensatz zu [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Text-Abschnittsformatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective)-Methode verwenden, die eine [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getVersion()](#getVersion--) |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesbarer long.

**Rückgabe:**  
long