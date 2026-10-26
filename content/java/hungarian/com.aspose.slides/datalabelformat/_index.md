---
title: DataLabelFormat
second_title: Aspose.Slides Java API referencia
description: A DataLabel formázási beállításait képviseli.
type: docs
url: /hu/com.aspose.slides/datalabelformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden implementált interfész:**
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

A DataLabel formázási beállításait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Olvasás/írás boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Olvasás/írás boolean. |
| [getNumberFormat()](#getNumberFormat--) | A DataLabels objektum formátum karakterláncát képviseli. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | A DataLabels objektum formátum karakterláncát képviseli. |
| [getFormat()](#getFormat--) | A data címke formátumát képviseli. |
| [getPosition()](#getPosition--) | A data címke pozícióját képviseli. |
| [setPosition(int value)](#setPosition-int-) | A data címke pozícióját képviseli. |
| [getShowLegendKey()](#getShowLegendKey--) | Egy adott diagram data címke legend kulcs megjelenítési viselkedését képviseli. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Egy adott diagram data címke legend kulcs megjelenítési viselkedését képviseli. |
| [getShowValue()](#getShowValue--) | Egy adott diagram data címke százalékos érték megjelenítési viselkedését képviseli. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Egy adott diagram data címke százalékos érték megjelenítési viselkedését képviseli. |
| [getShowCategoryName()](#getShowCategoryName--) | Egy adott diagram data címke kategórianév megjelenítési viselkedését képviseli. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Egy adott diagram data címke kategórianév megjelenítési viselkedését képviseli. |
| [getShowSeriesName()](#getShowSeriesName--) | Visszatér vagy beállít egy Boolean értéket, amely jelzi a sor neve megjelenítési viselkedését a diagram data címkéin. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Visszatér vagy beállít egy Boolean értéket, amely jelzi a sor neve megjelenítési viselkedését a diagram data címkéin. |
| [getShowPercentage()](#getShowPercentage--) | Egy adott diagram data címke százalékos érték megjelenítési viselkedését képviseli. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Egy adott diagram data címke százalékos érték megjelenítési viselkedését képviseli. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Egy adott diagram data címke buborékméret érték megjelenítési viselkedését képviseli. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Egy adott diagram data címke buborékméret érték megjelenítési viselkedését képviseli. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Egy adott diagram data címke vezetővonalak megjelenítési viselkedését képviseli. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Egy adott diagram data címke vezetővonalak megjelenítési viselkedését képviseli. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Egy adott diagram data címke cellaérték megjelenítési viselkedését képviseli. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Egy adott diagram data címke cellaérték megjelenítési viselkedését képviseli. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Meghatározza, hogy az adott diagram data címkéje adat-feliratként vagy data címkéként jelenik meg. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Meghatározza, hogy az adott diagram data címkéje adat-feliratként vagy data címkéként jelenik meg. |
| [getSeparator()](#getSeparator--) | Beállít vagy visszatér egy Variant értékkel, amely a diagram data címkéinek elválasztóját jelöli. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Beállít vagy visszatér egy Variant értékkel, amely a diagram data címkéinek elválasztóját jelöli. |
| [getTextFormat()](#getTextFormat--) | Visszatér a diagram szövegformátumával. |
| [getChart()](#getChart--) | Visszatér a diagrammal. |

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

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az IsNumberFormatLinkedToSource tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket az IsNumberFormatLinkedToSource tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" miatt minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() egyenlő lesz a val értékkel).

**Visszatér:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az IsNumberFormatLinkedToSource tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket az IsNumberFormatLinkedToSource tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" miatt minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

A DataLabels objektum formátum karakterláncát képviseli. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék NumberFormat tulajdonságának alapértelmezett értékét a DataLabelCollection gyűjteményben. Amikor ezt a tulajdonságot egy értékkel állítják be, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" miatt minden DataLabels.get_Item(i).getNumberFormat() egyenlő lesz a val értékkel).

**Visszatér:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

A DataLabels objektum formátum karakterláncát képviseli. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja az új adatcímkék NumberFormat tulajdonságának alapértelmezett értékét a DataLabelCollection gyűjteményben. Amikor ezt a tulajdonságot egy értékkel állítják be, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" miatt minden DataLabels.get_Item(i).getNumberFormat() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A data címke formátumát képviseli. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság az új adatcímkék alapértelmezett formátumát képviseli a DataLabelCollection gyűjteményben.

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

A data címke pozícióját képviseli. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a Position tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A Position a DataLabel objektumok pozícióját jelenti. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a Position tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" miatt minden DataLabels.get_Item(i).getPosition() egyenlő lesz a val értékkel).

**Visszatér:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

A data címke pozícióját képviseli. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a Position tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A Position a DataLabel objektumok pozícióját jelenti. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a Position tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setPosition(val);" miatt minden DataLabels.get_Item(i).getPosition() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

Egy adott diagram data címke legend kulcs megjelenítési viselkedését képviseli. True ha a data címke legend kulcs látható. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a ShowLegendKey tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" miatt minden DataLabels.get_Item(i).getShowLegendKey() egyenlő lesz a val értékkel).

**Visszatér:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

Egy adott diagram data címke legend kulcs megjelenítési viselkedését képviseli. True ha a data címke legend kulcs látható. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a ShowLegendKey tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" miatt minden DataLabels.get_Item(i).getShowLegendKey() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

Egy adott diagram data címke százalékos érték megjelenítési viselkedését képviseli. True megjeleníti a százalékos értéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowValue tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a ShowValue tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" miatt minden DataLabels.get_Item(i).getShowValue() egyenlő lesz a val értékkel).

**Visszatér:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

Egy adott diagram data címke százalékos érték megjelenítési viselkedését képviseli. True megjeleníti a százalékos értéket. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowValue tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a ShowValue tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" miatt minden DataLabels.get_Item(i).getShowValue() egyenlő lesz a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

Egy adott diagram data címke kategórianév megjelenítési viselkedését képviseli. True megjeleníti a kategórianév a diagram data címkéin. False elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság lekéri vagy beállítja a ShowCategoryName tulajdonság alapértelmezett értékét az új adatcímkéknél a DataLabelCollection gyűjteményben. A tulajdonság értékkel történő beállítása ugyanakkor ezt az értéket a ShowCategoryName tulajdonságra is alkalmazza minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" miatt minden DataLabels.get_Item(i).getShowCategoryName() egyenlő lesz a val értékkel).

**Visszatér:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

Egy adott diagram data címke kategórianév megjelenítési viselkedését képviseli. True megjeleníti a kategórianév a diagram data címkéin. False elrejti. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowCategoryName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowCategoryName tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ami miatt minden DataLabels.get_Item(i).getShowCategoryName() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

Egy Boolean értéket ad vissza vagy állít be, amely a diagram adatcímkéinél a sor név megjelenítésének viselkedését jelzi. Igaz, ha a sor nevét megjeleníti. Hamis, ha elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowSeriesName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowSeriesName tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ami miatt minden DataLabels.get_Item(i).getShowSeriesName() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

Egy Boolean értéket ad vissza vagy állít be, amely a diagram adatcímkéinél a sor név megjelenítésének viselkedését jelzi. Igaz, ha a sor nevét megjeleníti. Hamis, ha elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowSeriesName tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowSeriesName tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ami miatt minden DataLabels.get_Item(i).getShowSeriesName() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

Egy megadott diagram adatcímkéjének százalékérték megjelenítésének viselkedését képviseli. Igaz, ha a százalékértéket megjeleníti. Hamis, ha elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowPercentage tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowPercentage tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ami miatt minden DataLabels.get_Item(i).getShowPercentage() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

Egy megadott diagram adatcímkéjének százalékérték megjelenítésének viselkedését képviseli. Igaz, ha a százalékértéket megjeleníti. Hamis, ha elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowPercentage tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowPercentage tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ami miatt minden DataLabels.get_Item(i).getShowPercentage() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

Egy megadott diagram adatcímkéjének buborékméret érték megjelenítésének viselkedését képviseli. Igaz, ha a buborékméretet megjeleníti. Hamis, ha elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowBubbleSize tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowBubbleSize tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ami miatt minden DataLabels.get_Item(i).getShowBubbleSize() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

Egy megadott diagram adatcímkéjének buborékméret érték megjelenítésének viselkedését képviseli. Igaz, ha a buborékméretet megjeleníti. Hamis, ha elrejti. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowBubbleSize tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowBubbleSize tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ami miatt minden DataLabels.get_Item(i).getShowBubbleSize() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

Egy megadott diagram adatcímkéjének vezetővonalak megjelenítésének viselkedését képviseli. Igaz, ha a vezetővonalak megjelennek. Hamis, ha elrejtőnek. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLeaderLines tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLeaderLines tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ami miatt minden DataLabels.get_Item(i).getShowLeaderLines() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

Egy megadott diagram adatcímkéjének vezetővonalak megjelenítésének viselkedését képviseli. Igaz, ha a vezetővonalak megjelennek. Hamis, ha elrejtőnek. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLeaderLines tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLeaderLines tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ami miatt minden DataLabels.get_Item(i).getShowLeaderLines() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

Egy megadott diagram adatcímkéjének cellaérték megjelenítésének viselkedését képviseli. Igaz, ha a cellaérték megjelenik. Hamis, ha elrejtőnek. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelValueFromCell tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLabelValueFromCell tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ami miatt minden DataLabels.get_Item(i).getShowLabelValueFromCell() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

Egy megadott diagram adatcímkéjének cellaérték megjelenítésének viselkedését képviseli. Igaz, ha a cellaérték megjelenik. Hamis, ha elrejtőnek. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelValueFromCell tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLabelValueFromCell tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ami miatt minden DataLabels.get_Item(i).getShowLabelValueFromCell() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

Meghatározza, hogy a megadott diagram adatcímkéje adatkiírásként vagy adatcímkeként jelenik meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ami miatt minden DataLabels.get_Item(i).getShowLabelAsDataCallout() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

Meghatározza, hogy a megadott diagram adatcímkéje adatkiírásként vagy adatcímkeként jelenik meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vissza vagy állítja be az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a ShowLabelAsDataCallout tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ami miatt minden DataLabels.get_Item(i).getShowLabelAsDataCallout() egyenlő lesz a megadott értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

Egy Variantet állít be vagy ad vissza, amely a diagram adatcímkéinél használt elválasztót képviseli. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a Separator tulajdonság alapértelmezett értékét állítja be vagy adja vissza az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a Separator tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ami miatt minden DataLabels.get_Item(i).getSeparator() egyenlő lesz a megadott értékkel).

**Visszatérési érték:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

Egy Variantet állít be vagy ad vissza, amely a diagram adatcímkéinél használt elválasztót képviseli. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a Separator tulajdonság alapértelmezett értékét állítja be vagy adja vissza az új adatcímkék számára a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel történő beállítása szintén beállítja ezt az értéket a Separator tulajdonságra minden adatcímkére a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ami miatt minden DataLabels.get_Item(i).getSeparator() egyenlő lesz a megadott értékkel).
**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Visszaadja a diagram szövegformátumát. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatérési érték:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


Visszaadja a diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart)