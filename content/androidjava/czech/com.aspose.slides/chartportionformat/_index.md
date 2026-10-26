---
title: ChartPortionFormat
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech.
type: docs
url: /cs/com.aspose.slides/chartportionformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
```
public final class ChartPortionFormat extends BasePortionFormat implements IChartPortionFormat
```

Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech. Na rozdíl od [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textové části definovanými pro konkrétní část. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující "undefined".

Aby bylo možné získat efektivní hodnoty parametrů formátování včetně zděděných, musíte použít metodu [PortionFormat.getEffective](../../com.aspose.slides/portionformat\#getEffective), která vrací instanci [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

**Vrací:**
long