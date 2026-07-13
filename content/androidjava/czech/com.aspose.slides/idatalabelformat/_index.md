---
title: IDataLabelFormat
second_title: Aspose.Slides pro Android pomocí Java API
description: Reprezentuje možnosti formátování pro DataLabel.
type: docs
url: /cs/com.aspose.slides/idatalabelformat/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

Reprezentuje možnosti formátování pro DataLabel.
## Metody

| Metoda | Popis |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Číst/zapisovat boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Číst/zapisovat boolean. |
| [getNumberFormat()](#getNumberFormat--) | Reprezentuje řetězec formátu pro objekt DataLabels. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Reprezentuje řetězec formátu pro objekt DataLabels. |
| [getFormat()](#getFormat--) | Reprezentuje formát popisku dat. |
| [getPosition()](#getPosition--) | Reprezentuje pozici popisku dat. |
| [setPosition(int value)](#setPosition-int-) | Reprezentuje pozici popisku dat. |
| [getShowLegendKey()](#getShowLegendKey--) | Reprezentuje chování zobrazování legendového klíče popisku dat v určeném grafu. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Reprezentuje chování zobrazování legendového klíče popisku dat v určeném grafu. |
| [getShowValue()](#getShowValue--) | Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. |
| [getShowCategoryName()](#getShowCategoryName--) | Reprezentuje chování zobrazování názvu kategorie popisku dat v určeném grafu. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Reprezentuje chování zobrazování názvu kategorie popisku dat v určeném grafu. |
| [getShowSeriesName()](#getShowSeriesName--) | Vrací nebo nastavuje Boolean, který určuje chování zobrazování názvu řady pro popisky dat v grafu. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Vrací nebo nastavuje Boolean, který určuje chování zobrazování názvu řady pro popisky dat v grafu. |
| [getShowPercentage()](#getShowPercentage--) | Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Reprezentuje chování zobrazování hodnoty velikosti bubliny popisku dat v určeném grafu. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Reprezentuje chování zobrazování hodnoty velikosti bubliny popisku dat v určeném grafu. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Reprezentuje chování zobrazování čar vedoucích popisek dat v určeném grafu. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Reprezentuje chování zobrazování čar vedoucích popisek dat v určeném grafu. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Určuje, zda bude popisek dat v určeném grafu zobrazen jako datový výjezd nebo jako popisek dat. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Určuje, zda bude popisek dat v určeném grafu zobrazen jako datový výjezd nebo jako popisek dat. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Reprezentuje chování zobrazování hodnoty buňky popisku dat v určeném grafu. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Reprezentuje chování zobrazování hodnoty buňky popisku dat v určeném grafu. |
| [getSeparator()](#getSeparator--) | Nastavuje nebo vrací Variant, který představuje oddělovač používaný pro popisky dat v grafu. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Nastavuje nebo vrací Variant, který představuje oddělovač používaný pro popisky dat v grafu. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota pro vlastnost IsNumberFormatLinkedToSource u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val).

**Vrací:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se také nastaví tato hodnota pro vlastnost IsNumberFormatLinkedToSource u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" cause to all DataLabels.get_Item(i).isNumberFormatLinkedToSource() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Reprezentuje řetězec formátu pro objekt DataLabels. Číst/zapisovat String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection. Při nastavení této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost NumberFormat u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

**Vrací:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Reprezentuje řetězec formátu pro objekt DataLabels. Číst/zapisovat String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat v kolekci DataLabelCollection. Při nastavení této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost NumberFormat u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" causes all DataLabels.get_Item(i).getNumberFormat() to equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Reprezentuje formát popisku dat. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost představuje výchozí formát pro nové popisky dat v kolekci DataLabelCollection.

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Reprezentuje pozici popisku dat. Číst/zapisovat [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection. Reprezentuje pozici pro objekty DataLabel. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost Position u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Vrací:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Reprezentuje pozici popisku dat. Číst/zapisovat [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat v kolekci DataLabelCollection. Reprezentuje pozici pro objekty DataLabel. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost Position u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" cause to all DataLabels.get_Item(i).getPosition() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Reprezentuje chování zobrazování legendového klíče popisku dat v určeném grafu. True if the data label legend key is visible. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLegendKey u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Vrací:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Reprezentuje chování zobrazování legendového klíče popisku dat v určeném grafu. True if the data label legend key is visible. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLegendKey u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" cause to all DataLabels.get_Item(i).getShowLegendKey() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. True displays the percentage value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowValue u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Vrací:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. True displays the percentage value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowValue u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" cause to all DataLabels.get_Item(i).getShowValue() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Reprezentuje chování zobrazování názvu kategorie popisku dat v určeném grafu. True to display the category name for the data labels on a chart. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowCategoryName u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Vrací:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Reprezentuje chování zobrazování názvu kategorie popisku dat v určeném grafu. True to display the category name for the data labels on a chart. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowCategoryName u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Vrací nebo nastavuje Boolean, který určuje chování zobrazování názvu řady pro popisky dat v grafu. True to show the series name. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowSeriesName u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Vrací:**
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Vrací nebo nastavuje Boolean, který určuje chování zobrazování názvu řady pro popisky dat v grafu. True to show the series name. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowSeriesName u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. True displays the percentage value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowPercentage u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Vrací:**
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Reprezentuje chování zobrazování procentuální hodnoty popisku dat v určeném grafu. True displays the percentage value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowPercentage u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Reprezentuje chování zobrazování hodnoty velikosti bubliny popisku dat v určeném grafu. True displays the bubble size value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowBubbleSize u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Vrací:**
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Reprezentuje chování zobrazování hodnoty velikosti bubliny popisku dat v určeném grafu. True displays the bubble size value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowBubbleSize u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Reprezentuje chování zobrazování čar vedoucích popisek dat v určeném grafu. True displays the leader lines. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLeaderLines u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Vrací:**
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Reprezentuje chování zobrazování čar vedoucích popisek dat v určeném grafu. True displays the leader lines. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLeaderLines u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Určuje, zda bude popisek dat v určeném grafu zobrazen jako datový výjezd nebo jako popisek dat.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLabelAsDataCallout u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Vrací:**
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Určuje, zda bude popisek dat v určeném grafu zobrazen jako datový výjezd nebo jako popisek dat.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLabelAsDataCallout u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Reprezentuje chování zobrazování hodnoty buňky popisku dat v určeném grafu. True displays cell value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLabelValueFromCell u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Vrací:**
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Reprezentuje chování zobrazování hodnoty buňky popisku dat v určeném grafu. True displays cell value. False to hide. Číst/zapisovat boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost ShowLabelValueFromCell u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Nastavuje nebo vrací Variant, který představuje oddělovač používaný pro popisky dat v grafu. Číst/zapisovat String.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost Separator u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Vrací:**
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Nastavuje nebo vrací Variant, který představuje oddělovač používaný pro popisky dat v grafu. Číst/zapisovat String.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection, což je kolekce popisků dat, pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové popisky dat v kolekci DataLabelCollection. Nastavením této vlastnosti s hodnotou se tato hodnota také nastaví pro vlastnost Separator u všech popisků dat v kolekci DataLabelCollection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |