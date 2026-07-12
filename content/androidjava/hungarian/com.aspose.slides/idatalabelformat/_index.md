---
title: IDataLabelFormat
second_title: Aspose.Slides Android számára a Java API hivatkozás
description: A DataLabel formázási beállításait képviseli.
type: docs
url: /hu/com.aspose.slides/idatalabelformat/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

A DataLabel formázási beállításait képviseli.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Olvasás/írás logikai érték. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Olvasás/írás logikai érték. |
| [getNumberFormat()](#getNumberFormat--) | A DataLabels objektum formátumsztringjét képviseli. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | A DataLabels objektum formátumsztringjét képviseli. |
| [getFormat()](#getFormat--) | A adatcímke formátumát képviseli. |
| [getPosition()](#getPosition--) | Az adatcímke helyzetét képviseli. |
| [setPosition(int value)](#setPosition-int-) | Az adatcímke helyzetét képviseli. |
| [getShowLegendKey()](#getShowLegendKey--) | Egy megadott diagram adatcímkéjének legendakulcs megjelenítési viselkedését képviseli. |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | Egy megadott diagram adatcímkéjének legendakulcs megjelenítési viselkedését képviseli. |
| [getShowValue()](#getShowValue--) | Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [setShowValue(boolean value)](#setShowValue-boolean-) | Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [getShowCategoryName()](#getShowCategoryName--) | Egy megadott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | Egy megadott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. |
| [getShowSeriesName()](#getShowSeriesName--) | Visszaad vagy beállít egy logikai értéket, amely a diagram adatcímkéiben a sorozatnév megjelenítési viselkedését jelzi. |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | Visszaad vagy beállít egy logikai értéket, amely a diagram adatcímkéiben a sorozatnév megjelenítési viselkedését jelzi. |
| [getShowPercentage()](#getShowPercentage--) | Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. |
| [getShowBubbleSize()](#getShowBubbleSize--) | Egy megadott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését képviseli. |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | Egy megadott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését képviseli. |
| [getShowLeaderLines()](#getShowLeaderLines--) | Egy megadott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését képviseli. |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | Egy megadott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését képviseli. |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | Meghatározza, hogy egy megadott diagram adatcímkéje adatmegjegyzésként vagy adatcímkeként jelenik-e meg. |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | Meghatározza, hogy egy megadott diagram adatcímkéje adatmegjegyzésként vagy adatcímkeként jelenik-e meg. |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | Egy megadott diagram adatcímkéjének cellaérték megjelenítési viselkedését képviseli. |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | Egy megadott diagram adatcímkéjének cellaérték megjelenítési viselkedését képviseli. |
| [getSeparator()](#getSeparator--) | Beállít vagy visszaad egy Variant típusú értéket, amely a diagram adatcímkéiben használt elválasztót képviseli. |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | Beállít vagy visszaad egy Variant típusú értéket, amely a diagram adatcímkéiben használt elválasztót képviseli. |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkékre vonatkozóan a **IsNumberFormatLinkedToSource** alapértelmezett értékét adja vissza vagy állítja be. A tulajdonság értékének beállítása ezzel egyidejűleg beállítja az **IsNumberFormatLinkedToSource** értékét a DataLabelCollection-ben lévő összes adatcímkére (pl. „DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);” hatására minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() értéke **val** lesz).

**Visszatér:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkékre vonatkozóan a **IsNumberFormatLinkedToSource** alapértelmezett értékét adja vissza vagy állítja be. A tulajdonság értékének beállítása ezzel egyidejűleg beállítja az **IsNumberFormatLinkedToSource** értékét a DataLabelCollection-ben lévő összes adatcímkére (pl. „DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);” hatására minden DataLabels.get_Item(i).isNumberFormatLinkedToSource() értéke **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

A DataLabels objektum formátumsztringjét képviseli. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **NumberFormat** alapértelmezett értékét adja vissza vagy állítja be. Amikor az értékét beállítják, az érték a **NumberFormat** tulajdonságra is átkerül a DataLabelCollection-ban lévő összes adatcímkéhez (pl. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” hatására minden DataLabels.get_Item(i).getNumberFormat() **val** lesz).

**Visszatér:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

A DataLabels objektum formátumsztringjét képviseli. Olvasás/írás String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **NumberFormat** alapértelmezett értékét adja vissza vagy állítja be. Amikor az értékét beállítják, az érték a **NumberFormat** tulajdonságra is átkerül a DataLabelCollection-ban lévő összes adatcímkéhez (pl. „DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);” hatására minden DataLabels.get_Item(i).getNumberFormat() **val** lesz).

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

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék alapértelmezett formátumát képviseli.

**Visszatér:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Az adatcímke helyzetét képviseli. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **Position** alapértelmezett értékét adja vissza vagy állítja be. A **Position** a DataLabel objektumok helyzetét jelöli. Az érték beállítása ezen felül az összes adatcímke **Position** tulajdonságát is beállítja a DataLabelCollection-ban (pl. „DataLabels.getDefaultDataLabelFormat().setPosition(val)” hatására minden DataLabels.get_Item(i).getPosition() **val** lesz).

**Visszatér:**  
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Az adatcímke helyzetét képviseli. Olvasás/írás [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **Position** alapértelmezett értékét adja vissza vagy állítja be. A **Position** a DataLabel objektumok helyzetét jelöli. Az érték beállítása ezen felül az összes adatcímke **Position** tulajdonságát is beállítja a DataLabelCollection-ban (pl. „DataLabels.getDefaultDataLabelFormat().setPosition(val)” hatására minden DataLabels.get_Item(i).getPosition() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

Egy megadott diagram adatcímkéjének legendakulcs megjelenítési viselkedését képviseli. True érték esetén a legendakulcs látható. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLegendKey** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLegendKey** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” hatására minden DataLabels.get_Item(i).getShowLegendKey() **val** lesz).

**Visszatér:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

Egy megadott diagram adatcímkéjének legendakulcs megjelenítési viselkedését képviseli. True érték esetén a legendakulcs látható. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLegendKey** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLegendKey** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);” hatására minden DataLabels.get_Item(i).getShowLegendKey() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. True érték esetén a százalékos érték látható. False érték esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowValue** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowValue** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);” hatására minden DataLabels.get_Item(i).getShowValue() **val** lesz).

**Visszatér:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. True érték esetén a százalékos érték látható. False érték esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowValue** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowValue** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowValue(val);” hatására minden DataLabels.get_Item(i).getShowValue() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

Egy megadott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. True érték esetén a kategórianév látható. False érték esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowCategoryName** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowCategoryName** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);” hatására minden DataLabels.get_Item(i).getShowCategoryName() **val** lesz).

**Visszatér:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

Egy megadott diagram adatcímkéjének kategórianév megjelenítési viselkedését képviseli. True érték esetén a kategórianév látható. False érték esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowCategoryName** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowCategoryName** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);” hatására minden DataLabels.get_Item(i).getShowCategoryName() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

Visszaad vagy beállít egy logikai értéket, amely a diagram adatcímkéiben a sorozatnév megjelenítési viselkedését jelzi. True esetén a sorozatnév látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowSeriesName** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowSeriesName** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);” hatására minden DataLabels.get_Item(i).getShowSeriesName() **val** lesz).

**Visszatér:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

Visszaad vagy beállít egy logikai értéket, amely a diagram adatcímkéiben a sorozatnév megjelenítési viselkedését jelzi. True esetén a sorozatnév látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowSeriesName** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowSeriesName** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);” hatására minden DataLabels.get_Item(i).getShowSeriesName() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. True esetén a százalékos érték látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowPercentage** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowPercentage** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);” hatására minden DataLabels.get_Item(i).getShowPercentage() **val** lesz).

**Visszatér:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

Egy megadott diagram adatcímkéjének százalékos érték megjelenítési viselkedését képviseli. True esetén a százalékos érték látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowPercentage** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowPercentage** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);” hatására minden DataLabels.get_Item(i).getShowPercentage() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

Egy megadott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését képviseli. True esetén a buborékméret érték látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowBubbleSize** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowBubbleSize** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);” hatására minden DataLabels.get_Item(i).getShowBubbleSize() **val** lesz).

**Visszatér:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

Egy megadott diagram adatcímkéjének buborékméret érték megjelenítési viselkedését képviseli. True esetén a buborékméret érték látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowBubbleSize** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowBubbleSize** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);” hatására minden DataLabels.get_Item(i).getShowBubbleSize() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

Egy megadott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését képviseli. True esetén a vezetővonalak láthatóak. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLeaderLines** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLeaderLines** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);” hatására minden DataLabels.get_Item(i).getShowLeaderLines() **val** lesz).

**Visszatér:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

Egy megadott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését képviseli. True esetén a vezetővonalak láthatóak. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLeaderLines** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLeaderLines** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);” hatására minden DataLabels.get_Item(i).getShowLeaderLines() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

Meghatározza, hogy egy megadott diagram adatcímkéje adatmegjegyzésként vagy adatcímkeként jelenik-e meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLabelAsDataCallout** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLabelAsDataCallout** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);” hatására minden DataLabels.get_Item(i).getShowLabelAsDataCallout() **val** lesz).

**Visszatér:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

Meghatározza, hogy egy megadott diagram adatcímkéje adatmegjegyzésként vagy adatcímkeként jelenik-e meg.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLabelAsDataCallout** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLabelAsDataCallout** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);” hatására minden DataLabels.get_Item(i).getShowLabelAsDataCallout() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

Egy megadott diagram adatcímkéjének cellaérték megjelenítési viselkedését képviseli. True esetén a cellaérték látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLabelValueFromCell** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLabelValueFromCell** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);” hatására minden DataLabels.get_Item(i).getShowLabelValueFromCell() **val** lesz).

**Visszatér:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

Egy megadott diagram adatcímkéjének cellaérték megjelenítési viselkedését képviseli. True esetén a cellaérték látható. False esetén rejtett. Olvasás/írás logikai érték.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **ShowLabelValueFromCell** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **ShowLabelValueFromCell** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);” hatására minden DataLabels.get_Item(i).getShowLabelValueFromCell() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

Beállít vagy visszaad egy Variant típusú értéket, amely a diagram adatcímkéiben használt elválasztót képviseli. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **Separator** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **Separator** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setSeparator(val);” hatására minden DataLabels.get_Item(i).getSeparator() **val** lesz).

**Visszatér:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

Beállít vagy visszaad egy Variant típusú értéket, amely a diagram adatcímkéiben használt elválasztót képviseli. Olvasás/írás String.

--------------------

Ha ennek a DataLabelFormat objektumnak a szülője egy DataLabelCollection adatcímke-gyűjtemény, akkor ez a tulajdonság a DataLabelCollection-ben új adatcímkék **Separator** alapértelmezett értékét adja vissza vagy állítja be. Az érték beállítása ezen felül az összes adatcímke **Separator** tulajdonságát is beállítja (pl. „DataLabels.getDefaultDataLabelFormat().setSeparator(val);” hatására minden DataLabels.get_Item(i).getSeparator() **val** lesz).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |