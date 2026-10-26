---
title: ChartPortionFormat
second_title: Aspose.Slides Android számára a Java API hivatkozás
description: Ez az osztály tartalmazza a diagramokban használt diagramrész formázási tulajdonságait.
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

Ez az osztály tartalmazza a diagram részeformázási tulajdonságait, amelyeket diagramokban használnak. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-tól eltérően, az osztály összes tulajdonsága írható.

--------------------

Ez az osztály a szövegrész formázási tulajdonságainak visszaadására és kezelésére szolgál, amelyek a konkrét részre vonatkoznak. Ez azt jelenti, hogy értékek lekérésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket kap, amelyek „nem definiáltak”.

Az öröklött értékeket is magában foglaló tényleges formázási paraméterek értékének lekéréséhez a [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective) metódust kell használni, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long