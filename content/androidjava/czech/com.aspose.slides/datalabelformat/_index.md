---
title: DataLabelFormat
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje možnosti formátování pro DataLabel.
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

Představuje možnosti formátování pro DataLabel.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Čtení/Zápis boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Čtení/Zápis boolean. |
| [getNumberFormat()](#getNumberFormat--) | Represents the format string for the DataLabels object. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Represents the format string for the DataLabels object. |
| [getFormat()](#getFormat--) | Represents the format of the data label. |
| [getPosition()](#getPosition--) | Represents the position of the data label. |
| [setPosition(int value)](#setPosition-int-) | Represents the position of the data label. |
| [getShowLegendKey()](#getShowLegendKey--) | Represents a specified chart's data label legend key display behavior. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Represents a specified chart's data label legend key display behavior. |
| [getShowValue()](#getShowValue--) | Represents a specified chart's data label percentage value display behavior. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Represents a specified chart's data label percentage value display behavior. |
| [getShowCategoryName()](#getShowCategoryName--) | Represents a specified chart's data label category name display behavior. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Represents a specified chart's data label category name display behavior. |
| [getShowSeriesName()](#getShowSeriesName--) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. |
| [getShowPercentage()](#getShowPercentage--) | Represents a specified chart's data label percentage value display behavior. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Represents a specified chart's data label percentage value display behavior. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Represents a specified chart's data label bubble size value display behavior. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Represents a specified chart's data label bubble size value display behavior. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Represents a specified chart's data label leader lines display behavior. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Represents a specified chart's data label leader lines display behavior. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Represents a specified chart's data label cell value display behavior. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Represents a specified chart's data label cell value display behavior. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Determines either specified chart's data label will be displayed as data callout or as data label. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Determines either specified chart's data label will be displayed as data callout or as data label. |
| [getSeparator()](#getSeparator--) | Sets or returns a Variant representing the separator used for the data labels on a chart. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Sets or returns a Variant representing the separator used for the data labels on a chart. |
| [getTextFormat()](#getTextFormat--) | Returns chart text format. |
| [getChart()](#getChart--) | Returns the chart. |
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

Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost IsNumberFormatLinkedToSource u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" způsobí, že všechny DataLabels.get_Item(i).isNumberFormatLinkedToSource() jsou rovny val).

**Vrací:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti IsNumberFormatLinkedToSource pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost IsNumberFormatLinkedToSource u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" způsobí, že všechny DataLabels.get_Item(i).isNumberFormatLinkedToSource() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Představuje formátovací řetězec pro objekt DataLabels. Čtení/Zápis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat ve sbírce DataLabelCollection. Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" způsobí, že všechny DataLabels.get_Item(i).getNumberFormat() jsou rovny val).

**Vrací:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Představuje formátovací řetězec pro objekt DataLabels. Čtení/Zápis String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti NumberFormat pro nové popisky dat ve sbírce DataLabelCollection. Když je tato vlastnost nastavena na hodnotu, tato hodnota je také nastavena pro vlastnost NumberFormat u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" způsobí, že všechny DataLabels.get_Item(i).getNumberFormat() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Představuje formát popisku dat. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost představuje výchozí formát pro nové popisky dat ve sbírce DataLabelCollection.

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Představuje pozici popisku dat. Čtení/Zápis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat ve sbírce DataLabelCollection. Představuje pozici pro objekty DataLabel. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost Position u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" způsobí, že všechny DataLabels.get_Item(i).getPosition() jsou rovny val).

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Představuje pozici popisku dat. Čtení/Zápis [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Position pro nové popisky dat ve sbírce DataLabelCollection. Představuje pozici pro objekty DataLabel. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost Position u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" způsobí, že všechny DataLabels.get_Item(i).getPosition() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Představuje chování zobrazení legendy klíče popisku dat pro určitý graf. True pokud je klíč legendy popisku dat viditelný. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLegendKey u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLegendKey() jsou rovny val).

**Vrací:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Představuje chování zobrazení legendy klíče popisku dat pro určitý graf. True pokud je klíč legendy popisku dat viditelný. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLegendKey pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLegendKey u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLegendKey() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Představuje chování zobrazení procentuální hodnoty popisku dat pro určitý graf. True zobrazuje procentuální hodnotu. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowValue u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" způsobí, že všechny DataLabels.get_Item(i).getShowValue() jsou rovny val).

**Vrací:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Představuje chování zobrazení procentuální hodnoty popisku dat pro určitý graf. True zobrazuje procentuální hodnotu. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowValue pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowValue u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" způsobí, že všechny DataLabels.get_Item(i).getShowValue() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Představuje chování zobrazení názvu kategorie popisku dat pro určitý graf. True zobrazí název kategorie pro popisky dat v grafu. False jej skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowCategoryName u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowCategoryName() jsou rovny val).

**Vrací:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Představuje chování zobrazení názvu kategorie popisku dat pro určitý graf. True zobrazí název kategorie pro popisky dat v grafu. False jej skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowCategoryName pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowCategoryName u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowCategoryName() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Vrací nebo nastavuje Boolean určující chování zobrazení názvu řady pro popisky dat v grafu. True zobrazí název řady. False jej skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowSeriesName u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowSeriesName() jsou rovny val).

**Vrací:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Vrací nebo nastavuje Boolean určující chování zobrazení názvu řady pro popisky dat v grafu. True zobrazí název řady. False jej skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowSeriesName pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowSeriesName u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" způsobí, že všechny DataLabels.get_Item(i).getShowSeriesName() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Představuje chování zobrazení procentuální hodnoty popisku dat pro určitý graf. True zobrazuje procentuální hodnotu. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowPercentage u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" způsobí, že všechny DataLabels.get_Item(i).getShowPercentage() jsou rovny val).

**Vrací:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Představuje chování zobrazení procentuální hodnoty popisku dat pro určitý graf. True zobrazuje procentuální hodnotu. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowPercentage pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowPercentage u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" způsobí, že všechny DataLabels.get_Item(i).getShowPercentage() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Představuje chování zobrazení velikosti bubliny popisku dat pro určitý graf. True zobrazuje hodnotu velikosti bubliny. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowBubbleSize u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" způsobí, že všechny DataLabels.get_Item(i).getShowBubbleSize() jsou rovny val).

**Vrací:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Představuje chování zobrazení velikosti bubliny popisku dat pro určitý graf. True zobrazuje hodnotu velikosti bubliny. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowBubbleSize pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowBubbleSize u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" způsobí, že všechny DataLabels.get_Item(i).getShowBubbleSize() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Představuje chování zobrazení čáry ukazatele popisku dat pro určitý graf. True zobrazuje čáry ukazatelů. False je skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLeaderLines u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLeaderLines() jsou rovny val).

**Vrací:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Představuje chování zobrazení čáry ukazatele popisku dat pro určitý graf. True zobrazuje čáry ukazatelů. False je skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLeaderLines pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLeaderLines u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLeaderLines() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Představuje chování zobrazení hodnoty buňky popisku dat pro určitý graf. True zobrazuje hodnotu buňky. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLabelValueFromCell u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelValueFromCell() jsou rovny val).

**Vrací:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Představuje chování zobrazení hodnoty buňky popisku dat pro určitý graf. True zobrazuje hodnotu buňky. False ji skryje. Čtení/Zápis boolean.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelValueFromCell pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLabelValueFromCell u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelValueFromCell() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Určuje, zda bude popisek dat zobrazen jako datový výkřik nebo jako popisek dat.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLabelAsDataCallout u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelAsDataCallout() jsou rovny val).

**Vrací:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Určuje, zda bude popisek dat zobrazen jako datový výkřik nebo jako popisek dat.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti ShowLabelAsDataCallout pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost ShowLabelAsDataCallout u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" způsobí, že všechny DataLabels.get_Item(i).getShowLabelAsDataCallout() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Nastavuje nebo vrací Variant představující oddělovač používaný pro popisky dat v grafu. Čtení/Zápis String.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost Separator u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" způsobí, že všechny DataLabels.get_Item(i).getSeparator() jsou rovny val).

**Vrací:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Nastavuje nebo vrací Variant představující oddělovač používaný pro popisky dat v grafu. Čtení/Zápis String.

--------------------

Pokud je nadřazeným objektem tohoto DataLabelFormat objekt DataLabelCollection (sbírka popisků dat), pak tato vlastnost získá nebo nastaví výchozí hodnotu vlastnosti Separator pro nové popisky dat ve sbírce DataLabelCollection. Nastavení této vlastnosti s hodnotou také nastaví tuto hodnotu pro vlastnost Separator u všech popisků dat ve sbírce DataLabelCollection (tj. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" způsobí, že všechny DataLabels.get_Item(i).getSeparator() jsou rovny val).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Vrací formát textu grafu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)