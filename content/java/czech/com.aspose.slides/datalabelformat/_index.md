---
title: DataLabelFormat
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje možnosti formátování pro DataLabel.
type: docs
url: /cs/com.aspose.slides/datalabelformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

Reprezentuje možnosti formátování pro DataLabel.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Čtení/zápis boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Čtení/zápis boolean. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje řetězec formátu pro objekt DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje řetězec formátu pro objekt DataLabels. |
| [getFormat()](#getFormat--) | Reprezentuje formát popisku dat. |
| [getPosition()](#getPosition--) | Reprezentuje pozici popisku dat. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozici popisku dat. |
| [getShowLegendKey()](#getShowLegendKey--) | Reprezentuje chování zobrazení legendy klíče popisku dat pro konkrétní graf. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Reprezentuje chování zobrazení legendy klíče popisku dat pro konkrétní graf. |
| [getShowValue()](#getShowValue--) | Reprezentuje chování zobrazení procentuální hodnoty popisku dat pro konkrétní graf. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Reprezentuje chování zobrazení procentuální hodnoty popisku dat pro konkrétní graf. |
| [getShowCategoryName()](#getShowCategoryName--) | Reprezentuje chování zobrazení názvu kategorie popisku dat pro konkrétní graf. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Reprezentuje chování zobrazení názvu kategorie popisku dat pro konkrétní graf. |
| [getShowSeriesName()](#getShowSeriesName--) | Vrací nebo nastavuje Boolean, který určuje chování zobrazení názvu řady pro popisky dat v grafu. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Vrací nebo nastavuje Boolean, který určuje chování zobrazení názvu řady pro popisky dat v grafu. |
| [getShowPercentage()](#getShowPercentage--) | Reprezentuje chování zobrazení procentuální hodnoty popisku dat pro konkrétní graf. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Reprezentuje chování zobrazení procentuální hodnoty popisku dat pro konkrétní graf. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Reprezentuje chování zobrazení hodnoty velikosti bubliny popisku dat pro konkrétní graf. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Reprezentuje chování zobrazení hodnoty velikosti bubliny popisku dat pro konkrétní graf. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Reprezentuje chování zobrazení vodicích čar popisku dat pro konkrétní graf. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Reprezentuje chování zobrazení vodicích čar popisku dat pro konkrétní graf. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Reprezentuje chování zobrazení hodnoty buňky popisku dat pro konkrétní graf. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Reprezentuje chování zobrazení hodnoty buňky popisku dat pro konkrétní graf. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Určuje, zda bude popisek dat v konkrétním grafu zobrazen jako výzva dat nebo jako popisek dat. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Určuje, zda bude popisek dat v konkrétním grafu zobrazen jako výzva dat nebo jako popisek dat. |
| [getSeparator()](#getSeparator--) | Nastavuje nebo vrací Variant představující oddělovač použitého pro popisky dat v grafu. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Nastavuje nebo vrací Variant představující oddělovač použitého pro popisky dat v grafu. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu grafu. |
| [getChart()](#getChart--) | Vrací graf. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení long.

**Vrací:**
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost IsNumberFormatLinkedToSource všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);“ způsobí, že všechny DataLabels.get\_Item(i).isNumberFormatLinkedToSource() budou mít hodnotu val).

**Vrací:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost IsNumberFormatLinkedToSource všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);“ způsobí, že všechny DataLabels.get\_Item(i).isNumberFormatLinkedToSource() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Reprezentuje řetězec formátu pro objekt DataLabels. Čtení/zápis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection. Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);“ způsobí, že všechny DataLabels.get\_Item(i).getNumberFormat() budou mít hodnotu val).

**Vrací:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Reprezentuje řetězec formátu pro objekt DataLabels. Čtení/zápis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection. Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);“ způsobí, že všechny DataLabels.get\_Item(i).getNumberFormat() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Reprezentuje formát popisku dat. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost představuje výchozí formát pro nové popisky dat v kolekci DataLabelCollection.

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Reprezentuje pozici popisku dat. Čtení/zápis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection. Představuje pozici pro objekty DataLabel. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost Position všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setPosition(val);“ způsobí, že všechny DataLabels.get\_Item(i).getPosition() budou mít hodnotu val).

**Vrací:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Reprezentuje pozici popisku dat. Čtení/zápis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection. Představuje pozici pro objekty DataLabel. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost Position všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setPosition(val);“ způsobí, že všechny DataLabels.get\_Item(i).getPosition() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Reprezentuje chování zobrazení legendy klíče popisku dat pro konkrétní graf. True, pokud je legenda klíče popisku dat viditelná. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost ShowLegendKey všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);“ způsobí, že všechny DataLabels.get\_Item(i).getShowLegendKey() budou mít hodnotu val).

**Vrací:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Reprezentuje chování zobrazení legendy klíče popisku dat pro konkrétní graf. True, pokud je legenda klíče popisku dat viditelná. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost ShowLegendKey všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);“ způsobí, že všechny DataLabels.get\_Item(i).getShowLegendKey() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Reprezentuje chování zobrazení procentuální hodnoty popisku dat pro konkrétní graf. True zobrazí procentuální hodnotu. False ji skryje. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowValue pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost ShowValue všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);“ způsobí, že všechny DataLabels.get\_Item(i).getShowValue() budou mít hodnotu val).

**Vrací:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Reprezentuje chování zobrazení procentuální hodnoty popisku dat pro konkrétní graf. True zobrazí procentuální hodnotu. False ji skryje. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowValue pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost ShowValue všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);“ způsobí, že všechny DataLabels.get\_Item(i).getShowValue() budou mít hodnotu val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Reprezentuje chování zobrazení názvu kategorie popisku dat pro konkrétní graf. True zobrazí název kategorie pro popisky dat v grafu. False jej skryje. Čtení/zápis boolean.

--------------------

Pokud je rodičem tohoto objektu DataLabelFormat kolekce DataLabelCollection popisků dat, pak tato vlastnost získává nebo nastavuje výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti na hodnotu se tato hodnota také nastaví pro vlastnost ShowCategoryName všech popisků dat v kolekci DataLabelCollection (např. „DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);“ způsobí, že všechny DataLabels.get\_Item(i).getShowCategoryName() budou mít hodnotu val).

**Vrací:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Reprezentuje chování zobrazení názvu kategorie popisku dat pro konkrétní graf. True zobrazí název kategorie pro popisky dat v grafu. False jej skryje. Čtení/zápis boolean.

--------------------
Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowCategoryName pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowCategoryName() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Vrací nebo nastavuje Boolean, který určuje chování zobrazení názvu řady pro datové popisky v grafu. True pro zobrazení názvu řady. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowSeriesName pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowSeriesName() je hodnota rovna val).

**Návratová hodnota:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Vrací nebo nastavuje Boolean, který určuje chování zobrazení názvu řady pro datové popisky v grafu. True pro zobrazení názvu řady. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowSeriesName pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowSeriesName() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Reprezentuje chování zobrazení hodnoty procenta datového popisku v konkrétním grafu. True pro zobrazení procentní hodnoty. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowPercentage pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowPercentage() je hodnota rovna val).

**Návratová hodnota:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Reprezentuje chování zobrazení hodnoty procenta datového popisku v konkrétním grafu. True pro zobrazení procentní hodnoty. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowPercentage pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowPercentage() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Reprezentuje chování zobrazení hodnoty velikosti bubliny datového popisku v konkrétním grafu. True pro zobrazení velikosti bubliny. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowBubbleSize pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowBubbleSize() je hodnota rovna val).

**Návratová hodnota:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Reprezentuje chování zobrazení hodnoty velikosti bubliny datového popisku v konkrétním grafu. True pro zobrazení velikosti bubliny. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowBubbleSize pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowBubbleSize() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Reprezentuje chování zobrazení vodicích čar datového popisku v konkrétním grafu. True pro zobrazení vodicích čar. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowLeaderLines pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowLeaderLines() je hodnota rovna val).

**Návratová hodnota:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Reprezentuje chování zobrazení vodicích čar datového popisku v konkrétním grafu. True pro zobrazení vodicích čar. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowLeaderLines pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowLeaderLines() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Reprezentuje chování zobrazení hodnoty buňky datového popisku v konkrétním grafu. True pro zobrazení hodnoty buňky. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowLabelValueFromCell pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowLabelValueFromCell() je hodnota rovna val).

**Návratová hodnota:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Reprezentuje chování zobrazení hodnoty buňky datového popisku v konkrétním grafu. True pro zobrazení hodnoty buňky. False pro skrytí. Čtení / zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowLabelValueFromCell pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowLabelValueFromCell() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Určuje, zda bude datový popisek v konkrétním grafu zobrazen jako výzva dat nebo jako popisek.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowLabelAsDataCallout pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowLabelAsDataCallout() je hodnota rovna val).

**Návratová hodnota:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Určuje, zda bude datový popisek v konkrétním grafu zobrazen jako výzva dat nebo jako popisek.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti ShowLabelAsDataCallout pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" způsobí, že pro všechny DataLabels.get_Item(i).getShowLabelAsDataCallout() je hodnota rovna val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Nastavuje nebo vrací Variant představující oddělovač používaný pro datové popisky v grafu. Čtení / zápis String.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti Separator pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" způsobí, že pro všechny DataLabels.get_Item(i).getSeparator() je hodnota rovna val).

**Návratová hodnota:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Nastavuje nebo vrací Variant představující oddělovač používaný pro datové popisky v grafu. Čtení / zápis String.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka datových popisků), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové datové popisky ve sbírce DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota do vlastnosti Separator pro všechny datové popisky ve sbírce DataLabelCollection (např. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" způsobí, že pro všechny DataLabels.get_Item(i).getSeparator() je hodnota rovna val).
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Vrací formát textu grafu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Návratová hodnota:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Vrací graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Návratová hodnota:**
[IChart](../../com.aspose.slides/ichart)