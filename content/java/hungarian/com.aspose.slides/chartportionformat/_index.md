---
title: ChartPortionFormat
second_title: Aspose.Slides Java API referencia
description: Ez az osztály a diagramokban használt diagramrészlet formázási tulajdonságokat tartalmazza.
type: docs
url: /hu/com.aspose.slides/chartportionformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Minden megvalósított interfész:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

Ez az osztály a diagramokban használt diagramrészlet formázási tulajdonságokat tartalmazza. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-tól különbözően, az osztály összes tulajdonsága írható.

--------------------

Ez az osztály a konkrét részhez definiált szövegrészlet formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy értékek lekérésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket kapsz, amelyeket „nem definiált” -ként értelmeznek.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterértékek lekéréséhez a [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) metódust kell használni, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long