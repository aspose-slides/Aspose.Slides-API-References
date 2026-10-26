---
title: DataLabelFormat
second_title: Aspose.Slides Androidra vonatkozó Java API referencia
description: A DataLabel formázási beállításait reprezentálja.
type: docs
url: /hu/com.aspose.slides/datalabelformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

A DataLabel formázási beállításait reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Olvasás/írás boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Olvasás/írás boolean. |
| [getNumberFormat()](#getNumberFormat--) | A DataLabels objektum formátumkarakterláncát reprezentálja. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | A DataLabels objektum formátumkarakterláncát reprezentálja. |
| [getFormat()](#getFormat--) | Az adatcímke formátumát reprezentálja. |
| [getPosition()](#getPosition--) | Az adatcímke pozícióját reprezentálja. |
| [setPosition(int value)](#setPosition-int-) | Az adatcímke pozícióját reprezentálja. |
| [getShowLegendKey()](#getShowLegendKey--) | Egy meghatározott diagram adatcímkéjének legendakulcs megjelenítési viselkedését reprezentálja. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Egy meghatározott diagram adatcímkéjének legendakulcs megjelenítési viselkedését reprezentálja. |
| [getShowValue()](#getShowValue--) | Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. |
| [getShowCategoryName()](#getShowCategoryName--) | Egy meghatározott diagram adatcímkéjének kategórianév megjelenítési viselkedését reprezentálja. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Egy meghatározott diagram adatcímkéjének kategórianév megjelenítési viselkedését reprezentálja. |
| [getShowSeriesName()](#getShowSeriesName--) | Visszaad vagy beállít egy Boolean értéket, amely jelzi a sor neve megjelenítési viselkedését a diagram adatcímkéin. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Visszaad vagy beállít egy Boolean értéket, amely jelzi a sor neve megjelenítési viselkedését a diagram adatcímkéin. |
| [getShowPercentage()](#getShowPercentage--) | Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Egy meghatározott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését reprezentálja. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Egy meghatározott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését reprezentálja. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Egy meghatározott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését reprezentálja. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Egy meghatározott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését reprezentálja. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Egy meghatározott diagram adatcímkéjének cellaérték megjelenítési viselkedését reprezentálja. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Egy meghatározott diagram adatcímkéjének cellaérték megjelenítési viselkedését reprezentálja. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Meghatározza, hogy egy meghatározott diagram adatcímkéje adatkiáltásként vagy adatcímkeként jelenik-e meg. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Meghatározza, hogy egy meghatározott diagram adatcímkéje adatkiáltásként vagy adatcímkeként jelenik-e meg. |
| [getSeparator()](#getSeparator--) | Beállít vagy visszaad egy Variant-et, amely a diagram adatcímkéinek elválasztóját reprezentálja. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Beállít vagy visszaad egy Variant-et, amely a diagram adatcímkéinek elválasztóját reprezentálja. |
| [getTextFormat()](#getTextFormat--) | Visszaadja a diagram szövegformátumát. |
| [getChart()](#getChart--) | Visszaadja a diagramot. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatér:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection gyűjteményben az új adatcímkékhez az IsNumberFormatLinkedToSource tulajdonság alapértelmezett értékét adja vissza vagy állítja be. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be az IsNumberFormatLinkedToSource tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" hatására minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection gyűjteményben az új adatcímkékhez az IsNumberFormatLinkedToSource tulajdonság alapértelmezett értékét adja vissza vagy állítja be. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be az IsNumberFormatLinkedToSource tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" hatására minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

A DataLabels objektum formátumkarakterláncát reprezentálja. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection gyűjteményben az új adatcímkékhez a NumberFormat tulajdonság alapértelmezett értékét adja vissza vagy állítja be. Amikor ezt a tulajdonságot egy értékkel állítják be, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hatására minden DataLabels.get_Item(i).getNumberFormat() egyenlő lesz a val értékkel).

**Visszatér:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

A DataLabels objektum formátumkarakterláncát reprezentálja. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection gyűjteményben az új adatcímkékhez a NumberFormat tulajdonság alapértelmezett értékét adja vissza vagy állítja be. Amikor ezt a tulajdonságot egy értékkel állítják be, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" hatására minden DataLabels.get_Item(i).getNumberFormat() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Az adatcímke formátumát reprezentálja. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság az új adatcímkék alapértelmezett formátumát reprezentálja a DataLabelCollection gyűjteményben.

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Az adatcímke pozícióját reprezentálja. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a Position tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Az adatcímke objektumok pozícióját reprezentálja. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a Position tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" hatására minden DataLabels.get_Item(i).getPosition() egyenlő lesz a val értékkel).

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Az adatcímke pozícióját reprezentálja. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a Position tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Az adatcímke objektumok pozícióját reprezentálja. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a Position tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" hatására minden DataLabels.get_Item(i).getPosition() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Egy meghatározott diagram adatcímkéjének legendakulcs megjelenítési viselkedését reprezentálja. True ha a legendakulcs látható. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLegendKey tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLegendKey tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" hatására minden DataLabels.get_Item(i).getShowLegendKey() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Egy meghatározott diagram adatcímkéjének legendakulcs megjelenítési viselkedését reprezentálja. True ha a legendakulcs látható. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLegendKey tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLegendKey tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" hatására minden DataLabels.get_Item(i).getShowLegendKey() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. True megjeleníti a százalékos értéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowValue tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowValue tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" hatására minden DataLabels.get_Item(i).getShowValue() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. True megjeleníti a százalékos értéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowValue tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowValue tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" hatására minden DataLabels.get_Item(i).getShowValue() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Egy meghatározott diagram adatcímkéjének kategórianév megjelenítési viselkedését reprezentálja. True megjeleníti a kategórianévét a diagram adatcímkéin. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowCategoryName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowCategoryName tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" hatására minden DataLabels.get_Item(i).getShowCategoryName() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Egy meghatározott diagram adatcímkéjének kategórianév megjelenítési viselkedését reprezentálja. True megjeleníti a kategórianévét a diagram adatcímkéin. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowCategoryName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowCategoryName tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" hatására minden DataLabels.get_Item(i).getShowCategoryName() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Visszaad vagy beállít egy Boolean értéket, amely jelzi a sor neve megjelenítési viselkedését a diagram adatcímkéin. True megjeleníti a sor nevét. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowSeriesName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowSeriesName tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" hatására minden DataLabels.get_Item(i).getShowSeriesName() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Visszaad vagy beállít egy Boolean értéket, amely jelzi a sor neve megjelenítési viselkedését a diagram adatcímkéin. True megjeleníti a sor nevét. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowSeriesName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowSeriesName tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" hatására minden DataLabels.get_Item(i).getShowSeriesName() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. True megjeleníti a százalékos értéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowPercentage tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowPercentage tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" hatására minden DataLabels.get_Item(i).getShowPercentage() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Egy meghatározott diagram adatcímkéjének százalékos érték megjelenítési viselkedését reprezentálja. True megjeleníti a százalékos értéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowPercentage tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowPercentage tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" hatására minden DataLabels.get_Item(i).getShowPercentage() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Egy meghatározott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését reprezentálja. True megjeleníti a buborékméretet. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowBubbleSize tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowBubbleSize tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" hatására minden DataLabels.get_Item(i).getShowBubbleSize() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Egy meghatározott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését reprezentálja. True megjeleníti a buborékméretet. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowBubbleSize tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowBubbleSize tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" hatására minden DataLabels.get_Item(i).getShowBubbleSize() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Egy meghatározott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését reprezentálja. True megjeleníti a vezetővonalakat. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLeaderLines tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLeaderLines tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" hatására minden DataLabels.get_Item(i).getShowLeaderLines() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Egy meghatározott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését reprezentálja. True megjeleníti a vezetővonalakat. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLeaderLines tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLeaderLines tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" hatására minden DataLabels.get_Item(i).getShowLeaderLines() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Egy meghatározott diagram adatcímkéjének cellaérték megjelenítési viselkedését reprezentálja. True megjeleníti a cellaértéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelValueFromCell tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLabelValueFromCell tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" hatására minden DataLabels.get_Item(i).getShowLabelValueFromCell() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Egy meghatározott diagram adatcímkéjének cellaérték megjelenítési viselkedését reprezentálja. True megjeleníti a cellaértéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelValueFromCell tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLabelValueFromCell tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" hatására minden DataLabels.get_Item(i).getShowLabelValueFromCell() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Meghatározza, hogy egy meghatározott diagram adatcímkéje adatkiáltásként vagy adatcímkeként jelenik-e meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLabelAsDataCallout tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" hatására minden DataLabels.get_Item(i).getShowLabelAsDataCallout() egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Meghatározza, hogy egy meghatározott diagram adatcímkéje adatkiáltásként vagy adatcímkeként jelenik-e meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a ShowLabelAsDataCallout tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" hatására minden DataLabels.get_Item(i).getShowLabelAsDataCallout() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Beállít vagy visszaad egy Variant-et, amely a diagram adatcímkéinek elválasztóját reprezentálja. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a Separator tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a Separator tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" hatására minden DataLabels.get_Item(i).getSeparator() egyenlő lesz a val értékkel).

**Visszatér:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Beállít vagy visszaad egy Variant-et, amely a diagram adatcímkéinek elválasztóját reprezentálja. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a Separator tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása ugyanazzal az értékkel állítja be a Separator tulajdonságot a DataLabelCollection gyűjteményben lévő összes adatcímke esetén (pl. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" hatására minden DataLabels.get_Item(i).getSeparator() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Visszaadja a diagram szövegformátumát. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatér:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)