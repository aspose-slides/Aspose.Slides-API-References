---
title: IDataLabelFormat
second_title: Aspose.Slides for Java API referencia
description: A DataLabel formázási beállításait jelöli.
type: docs
url: /hu/com.aspose.slides/idatalabelformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

A DataLabel formázási lehetőségeit képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Olvasás/írás boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Olvasás/írás boolean. |
| [getNumberFormat()](#getNumberFormat--) | A DataLabels objektum formátum karakterláncát képviseli. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | A DataLabels objektum formátum karakterláncát képviseli. |
| [getFormat()](#getFormat--) | Az adatcímke formátumát képviseli. |
| [getPosition()](#getPosition--) | Az adatcímke helyzetét képviseli. |
| [setPosition(int value)](#setPosition-int-) | Az adatcímke helyzetét képviseli. |
| [getShowLegendKey()](#getShowLegendKey--) | Egy adott diagram adatcímkéjének jelmagyarázat kulcs megjelenítési viselkedését képviseli. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Egy adott diagram adatcímkéjének jelmagyarázat kulcs megjelenítési viselkedését képviseli. |
| [getShowValue()](#getShowValue--) | Egy adott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Egy adott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [getShowCategoryName()](#getShowCategoryName--) | Egy adott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Egy adott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. |
| [getShowSeriesName()](#getShowSeriesName--) | Visszaad vagy beállít egy Boolean értéket, amely jelzi a sorozatnevek megjelenítési viselkedését a diagram adatcímkéin. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Visszaad vagy beállít egy Boolean értéket, amely jelzi a sorozatnevek megjelenítési viselkedését a diagram adatcímkéin. |
| [getShowPercentage()](#getShowPercentage--) | Egy adott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Egy adott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Egy adott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését képviseli. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Egy adott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését képviseli. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Egy adott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését képviseli. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Egy adott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését képviseli. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Meghatározza, hogy egy adott diagram adatcímkéje adatfelhívásként vagy adatcímkeként jelenik meg. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Meghatározza, hogy egy adott diagram adatcímkéje adatfelhívásként vagy adatcímkeként jelenik meg. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Egy adott diagram adatcímkéjének cellaérték megjelenítési viselkedését képviseli. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Egy adott diagram adatcímkéjének cellaérték megjelenítési viselkedését képviseli. |
| [getSeparator()](#getSeparator--) | Beállít vagy visszaad egy Variant-et, amely a diagram adatcímkéihez használt elválasztót képviseli. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Beállít vagy visszaad egy Variant-et, amely a diagram adatcímkéihez használt elválasztót képviseli. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri az IsNumberFormatLinkedToSource tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket az IsNumberFormatLinkedToSource tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" okozza, hogy minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() egyenlő legyen a val értékkel).

**Visszatér:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri az IsNumberFormatLinkedToSource tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket az IsNumberFormatLinkedToSource tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);" okozza, hogy minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() egyenlő legyen a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

A DataLabels objektum formátum karakterláncát képviseli. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a NumberFormat tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. Amikor ez a tulajdonság értékkel van beállítva, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" okozza, hogy minden DataLabels.get_Item(i).getNumberFormat() egyenlő legyen a val értékkel).

**Visszatér:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

A DataLabels objektum formátum karakterláncát képviseli. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a NumberFormat tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. Amikor ez a tulajdonság értékkel van beállítva, az érték ugyanúgy beállításra kerül a NumberFormat tulajdonságra az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" okozza, hogy minden DataLabels.get_Item(i).getNumberFormat() egyenlő legyen a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A adatcímke formátumát képviseli. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság az új adatcímkék alapértelmezett formátumát képviseli a DataLabelCollection gyűjteményben.

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Az adatcímke helyzetét képviseli. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a Position tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. Az adatcímke objektumok helyzetét adja meg. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a Position tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" okozza, hogy minden DataLabels.get_Item(i).getPosition() egyenlő legyen a val értékkel).

**Visszatér:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Az adatcímke helyzetét képviseli. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a Position tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. Az adatcímke objektumok helyzetét adja meg. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a Position tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setPosition(val)" okozza, hogy minden DataLabels.get_Item(i).getPosition() egyenlő legyen a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Egy adott diagram adatcímkéjének jelmagyarázat kulcs megjelenítési viselkedését képviseli. Igaz, ha a jelmagyarázat kulcs látható. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a ShowLegendKey tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" okozza, hogy minden DataLabels.get_Item(i).getShowLegendKey() egyenlő legyen a val értékkel).

**Visszatér:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Egy adott diagram adatcímkéjének jelmagyarázat kulcs megjelenítési viselkedését képviseli. Igaz, ha a jelmagyarázat kulcs látható. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a ShowLegendKey tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a ShowLegendKey tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" okozza, hogy minden DataLabels.get_Item(i).getShowLegendKey() egyenlő legyen a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Egy adott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. Igaz, ha a százalékos érték megjelenik. Hamis a rejtéshez. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a ShowValue tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a ShowValue tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" okozza, hogy minden DataLabels.get_Item(i).getShowValue() egyenlő legyen a val értékkel).

**Visszatér:**
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Egy adott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. Igaz, ha a százalékos érték megjelenik. Hamis a rejtéshez. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a ShowValue tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a ShowValue tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" okozza, hogy minden DataLabels.get_Item(i).getShowValue() egyenlő legyen a val értékkel).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Egy adott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. Igaz, ha a kategórianév megjelenik a diagram adatcímkéin. Hamis a rejtéshez. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság beállítja vagy lekéri a ShowCategoryName tulajdonság alapértelmezett értékét az új adatcímkékre a DataLabelCollection gyűjteményben. A tulajdonság értékével történő beállítás ugyanakkor ezt az értéket a ShowCategoryName tulajdonságra is átállítja az összes adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" okozza, hogy minden DataLabels.get_Item(i).getShowCategoryName() egyenlő legyen a val értékkel).

**Visszatér:**
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Egy adott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. Igaz, ha a kategórianév megjelenik a diagram adatcímkéin. Hamis a rejtéshez. Olvasás/írás boolean.

--------------------
Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowCategoryName tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowCategoryName tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowCategoryName() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```


Visszaad vagy beállít egy Boolean értéket, amely meghatározza a sor nevét megjelenítő viselkedést az adatcímkékben egy diagramon. True a sor neve megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowSeriesName tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowSeriesName tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowSeriesName() értéke egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```


Visszaad vagy beállít egy Boolean értéket, amely meghatározza a sor nevét megjelenítő viselkedést az adatcímkékben egy diagramon. True a sor neve megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowSeriesName tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowSeriesName tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowSeriesName() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```


Egy megadott diagram adatcímkéinek százalékérték-megjelenítési viselkedését reprezentálja. True a százalékérték megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowPercentage tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowPercentage tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowPercentage() értéke egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```


Egy megadott diagram adatcímkéinek százalékérték-megjelenítési viselkedését reprezentálja. True a százalékérték megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowPercentage tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowPercentage tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowPercentage() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```


Egy megadott diagram adatcímkéinek buborékméret-érték-megjelenítési viselkedését reprezentálja. True a buborékméret értéke megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowBubbleSize tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowBubbleSize tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowBubbleSize() értéke egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```


Egy megadott diagram adatcímkéinek buborékméret-érték-megjelenítési viselkedését reprezentálja. True a buborékméret értéke megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowBubbleSize tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowBubbleSize tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowBubbleSize() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```


Egy megadott diagram adatcímkéinek vezetéssorok megjelenítési viselkedését reprezentálja. True a vezetéssorok megjelennek. False el vannak rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowLeaderLines tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLeaderLines tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowLeaderLines() értéke egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```


Egy megadott diagram adatcímkéinek vezetéssorok megjelenítési viselkedését reprezentálja. True a vezetéssorok megjelennek. False el vannak rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowLeaderLines tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLeaderLines tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowLeaderLines() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```


Meghatározza, hogy egy megadott diagram adatcímkéje adatbuborékként vagy adatcímkeként jelenik meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLabelAsDataCallout tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowLabelAsDataCallout() értéke egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```


Meghatározza, hogy egy megadott diagram adatcímkéje adatbuborékként vagy adatcímkeként jelenik meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowLabelAsDataCallout tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLabelAsDataCallout tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowLabelAsDataCallout() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```


Egy megadott diagram adatcímkék cellaértékének megjelenítési viselkedését reprezentálja. True a cellaérték megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowLabelValueFromCell tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLabelValueFromCell tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowLabelValueFromCell() értéke egyenlő lesz a val értékkel).

**Visszatér:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```


Egy megadott diagram adatcímkék cellaértékének megjelenítési viselkedését reprezentálja. True a cellaérték megjelenik. False el van rejtve. Olvasás/írás boolean.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a ShowLabelValueFromCell tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a ShowLabelValueFromCell tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" ennek eredményeként minden DataLabels.get_Item(i).getShowLabelValueFromCell() értéke egyenlő lesz a val értékkel).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```


Beállít vagy visszaad egy Variant értéket, amely a diagram adatcímkéinek elválasztóját képviseli. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a Separator tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a Separator tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ennek eredményeként minden DataLabels.get_Item(i).getSeparator() értéke egyenlő lesz a val értékkel).

**Visszatér:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```


Beállít vagy visszaad egy Variant értéket, amely a diagram adatcímkéinek elválasztóját képviseli. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímkék gyűjteménye, akkor ez a tulajdonság a Separator tulajdonság alapértelmezett értékét adja vagy állítja be az új adatcímkékhez a DataLabelCollection gyűjteményben. Ennek a tulajdonságnak az értékkel való beállítása ugyanakkor ezt az értéket a Separator tulajdonságra állítja minden adatcímkénél a DataLabelCollection gyűjteményben (pl. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" ennek eredményeként minden DataLabels.get_Item(i).getSeparator() értéke egyenlő lesz a val értékkel).
**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |