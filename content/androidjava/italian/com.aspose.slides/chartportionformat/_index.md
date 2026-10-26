---
title: ChartPortionFormat
second_title: Aspose.Slides per Android via Riferimento API Java
description: Questa classe contiene le proprietà di formattazione della porzione del grafico utilizzate nei grafici.
type: docs
url: /it/com.aspose.slides/chartportionformat/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

Questa classe contiene le proprietà di formattazione della porzione del grafico utilizzate nei grafici. A differenza di [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono modificabili.

--------------------

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Questo significa che non viene applicata alcuna ereditarietà quando si ottengono i valori, quindi nella maggior parte dei casi otterrai valori che significano "undefined".

Per ottenere i valori effettivi dei parametri di formattazione, inclusi quelli ereditati, è necessario utilizzare il metodo [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) che restituisce un'istanza [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long