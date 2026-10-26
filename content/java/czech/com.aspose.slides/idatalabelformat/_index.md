---
title: IDataLabelFormat
second_title: Reference API Aspose.Slides pro Java
description: Reprezentuje možnosti formátování pro DataLabel.
type: docs
url: /cs/com.aspose.slides/idatalabelformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Representuje možnosti formátování pro DataLabel.
## Metody

| Metoda | Popis |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Čtení/zápis boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Čtení/zápis boolean. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje formátovací řetězec pro objekt DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje formátovací řetězec pro objekt DataLabels. |
| [getFormat()](#getFormat--) | Reprezentuje formát popisky dat. |
| [getPosition()](#getPosition--) | Reprezentuje pozici popisky dat. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozici popisky dat. |
| [getShowLegendKey()](#getShowLegendKey--) | Reprezentuje chování zobrazování legendárního klíče popisky dat ve specifikovaném grafu. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Reprezentuje chování zobrazování legendárního klíče popisky dat ve specifikovaném grafu. |
| [getShowValue()](#getShowValue--) | Reprezentuje chování zobrazování procentuální hodnoty popisky dat ve specifikovaném grafu. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Reprezentuje chování zobrazování procentuální hodnoty popisky dat ve specifikovaném grafu. |
| [getShowCategoryName()](#getShowCategoryName--) | Reprezentuje chování zobrazování názvu kategorie popisky dat ve specifikovaném grafu. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Reprezentuje chování zobrazování názvu kategorie popisky dat ve specifikovaném grafu. |
| [getShowSeriesName()](#getShowSeriesName--) | Vrací nebo nastavuje Boolean, který určuje, zda se název řady zobrazí u popisek dat v grafu. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Vrací nebo nastavuje Boolean, který určuje, zda se název řady zobrazí u popisek dat v grafu. |
| [getShowPercentage()](#getShowPercentage--) | Reprezentuje chování zobrazování procentuální hodnoty popisky dat ve specifikovaném grafu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Reprezentuje chování zobrazování procentuální hodnoty popisky dat ve specifikovaném grafu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Reprezentuje chování zobrazování hodnoty velikosti bubliny popisky dat ve specifikovaném grafu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Reprezentuje chování zobrazování hodnoty velikosti bubliny popisky dat ve specifikovaném grafu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Reprezentuje chování zobrazování čar vedoucích popisku dat ve specifikovaném grafu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Reprezentuje chování zobrazování čar vedoucích popisku dat ve specifikovaném grafu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Určuje, zda bude popiska dat ve specifikovaném grafu zobrazena jako výzva k datům nebo jako samotná popiska. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Určuje, zda bude popiska dat ve specifikovaném grafu zobrazena jako výzva k datům nebo jako samotná popiska. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Reprezentuje chování zobrazování hodnoty buňky popisky dat ve specifikovaném grafu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Reprezentuje chování zobrazování hodnoty buňky popisky dat ve specifikovaném grafu. |
| [getSeparator()](#getSeparator--) | Nastavuje nebo vrací Variant představující oddělovač používaný pro popisky dat v grafu. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Nastavuje nebo vrací Variant představující oddělovač používaný pro popisky dat v grafu. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost IsNumberFormatLinkedToSource všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" způsobí, že všechny DataLabels.get_Item(i).isNumberFormatLinkedToSource() budou mít hodnotu val).

**Vrací:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost IsNumberFormatLinkedToSource všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" způsobí, že všechny DataLabels.get_Item(i).isNumberFormatLinkedToSource() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Reprezentuje formátovací řetězec pro objekt DataLabels. Čtení/zápis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection. Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" způsobí, že všechny DataLabels.get_Item(i).getNumberFormat() budou mít hodnotu val).

**Vrací:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Reprezentuje formátovací řetězec pro objekt DataLabels. Čtení/zápis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection. Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" způsobí, že všechny DataLabels.get_Item(i).getNumberFormat() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje formát popisky dat. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost představuje výchozí formát pro nové popisky dat v kolekci DataLabelCollection.

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Reprezentuje pozici popisky dat. Čtení/zápis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection. Reprezentuje pozici pro objekty DataLabel. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost Position všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" způsobí, že všechny DataLabels.get_Item(i).getPosition() budou mít hodnotu val).

**Vrací:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Reprezentuje pozici popisky dat. Čtení/zápis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection. Reprezentuje pozici pro objekty DataLabel. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost Position všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" způsobí, že všechny DataLabels.get_Item(i).getPosition() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Reprezentuje chování zobrazování legendárního klíče popisky dat ve specifikovaném grafu. True pokud je legendární klíč popisky dat viditelný. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLegendKey všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLegendKey() budou mít hodnotu val).

**Vrací:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Reprezentuje chování zobrazování legendárního klíče popisky dat ve specifikovaném grafu. True pokud je legendární klíč popisky dat viditelný. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLegendKey všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLegendKey() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Reprezentuje chování zobrazování procentuální hodnoty popisky dat ve specifikovaném grafu. True zobrazí procentuální hodnotu. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowValue všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" způsobí, že všechny DataLabels.get_Item(i).getShowValue() budou mít hodnotu val).

**Vrací:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Reprezentuje chování zobrazování procentuální hodnoty popisky dat ve specifikovaném grafu. True zobrazí procentuální hodnotu. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowValue všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" způsobí, že všechny DataLabels.get_Item(i).getShowValue() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Reprezentuje chování zobrazování názvu kategorie popisky dat ve specifikovaném grafu. True pro zobrazení názvu kategorie popisky dat v grafu. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující popisky dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowCategoryName všech popisků dat v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowCategoryName() budou mít hodnotu val).

**Vrací:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Reprezentuje chování zobrazování názvu kategorie popisky dat ve specifikovaném grafu. True pro zobrazení názvu kategorie popisky dat v grafu. False pro skrytí. Čtení/zápis boolean.

--------------------
Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowCategoryName pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowCategoryName() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Vrací nebo nastavuje Boolean, který udává chování zobrazování názvu řady pro datové popisky v grafu. True pro zobrazení názvu řady. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowSeriesName pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowSeriesName() jsou rovny val).

**Vrací:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Vrací nebo nastavuje Boolean, který udává chování zobrazování názvu řady pro datové popisky v grafu. True pro zobrazení názvu řady. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowSeriesName pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowSeriesName() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Reprezentuje chování zobrazování procentuální hodnoty datového popisku v konkrétním grafu. True zobrazuje procentuální hodnotu. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowPercentage pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" způsobí, že všechny DataLabels.get_Item(i).getShowPercentage() jsou rovny val).

**Vrací:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Reprezentuje chování zobrazování procentuální hodnoty datového popisku v konkrétním grafu. True zobrazuje procentuální hodnotu. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowPercentage pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" způsobí, že všechny DataLabels.get_Item(i).getShowPercentage() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Reprezentuje chování zobrazování velikosti bubliny datového popisku v konkrétním grafu. True zobrazuje hodnotu velikosti bubliny. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowBubbleSize pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" způsobí, že všechny DataLabels.get_Item(i).getShowBubbleSize() jsou rovny val).

**Vrací:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Reprezentuje chování zobrazování velikosti bubliny datového popisku v konkrétním grafu. True zobrazuje hodnotu velikosti bubliny. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowBubbleSize pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" způsobí, že všechny DataLabels.get_Item(i).getShowBubbleSize() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Reprezentuje chování zobrazování čar spojnic datových popisků v konkrétním grafu. True zobrazuje čáry spojnic. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowLeaderLines pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLeaderLines() jsou rovny val).

**Vrací:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Reprezentuje chování zobrazování čar spojnic datových popisků v konkrétním grafu. True zobrazuje čáry spojnic. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowLeaderLines pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLeaderLines() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Určuje, zda bude datový popisek v konkrétním grafu zobrazen jako výzva k datům nebo jako samotný popisek.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowLabelAsDataCallout pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelAsDataCallout() jsou rovny val).

**Vrací:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Určuje, zda bude datový popisek v konkrétním grafu zobrazen jako výzva k datům nebo jako samotný popisek.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowLabelAsDataCallout pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelAsDataCallout() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Reprezentuje chování zobrazování hodnoty buňky datového popisku v konkrétním grafu. True zobrazuje hodnotu buňky. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowLabelValueFromCell pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelValueFromCell() jsou rovny val).

**Vrací:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Reprezentuje chování zobrazování hodnoty buňky datového popisku v konkrétním grafu. True zobrazuje hodnotu buňky. False pro skrytí. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost ShowLabelValueFromCell pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelValueFromCell() jsou rovny val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Nastavuje nebo vrací Variant představující oddělovač používaný pro datové popisky v grafu. Čtení/zápis String.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost Separator pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" způsobí, že všechny DataLabels.get_Item(i).getSeparator() jsou rovny val).

**Vrací:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Nastavuje nebo vrací Variant představující oddělovač používaný pro datové popisky v grafu. Čtení/zápis String.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection obsahující datové popisky, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové datové popisky v kolekci DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu na vlastnost Separator pro všechny datové popisky v kolekci DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" způsobí, že všechny DataLabels.get_Item(i).getSeparator() jsou rovny val).
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |