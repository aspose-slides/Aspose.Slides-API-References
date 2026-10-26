---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /cs/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Representuje uzel diagramu SmartArt.
## Metody

| Metoda | Popis |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Vrací kolekce všech podřízených uzlů aktuálního uzlu. |
| [getShapes()](#getShapes--) | Vrací kolekce všech tvarů spojených s uzlem. |
| [getTextFrame()](#getTextFrame--) | Vrací nebo nastavuje text uzlu. |
| [isAssistant()](#isAssistant--) | Vrací nebo nastavuje uzel jako asistenta. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Vrací nebo nastavuje uzel jako asistenta. |
| [getLevel()](#getLevel--) | Vrací úroveň vnoření uzlu. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro odrážku uzlu. |
| [getPosition()](#getPosition--) | Vrací nebo nastavuje nulově-indexovanou pozici uzlu mezi sourozeneckými uzly. |
| [setPosition(int value)](#setPosition-int-) | Vrací nebo nastavuje nulově-indexovanou pozici uzlu mezi sourozeneckými uzly. |
| [isHidden()](#isHidden--) | Vrací true, pokud je tento uzel v datovém modelu skrytý. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Vrací nebo nastavuje typ rozvržení organizačního diagramu spojený s aktuálním uzlem. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Vrací nebo nastavuje typ rozvržení organizačního diagramu spojený s aktuálním uzlem. |
| [remove()](#remove--) | Odstranit aktuální uzel. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Vrací kolekce všech podřízených uzlů aktuálního uzlu. Pouze pro čtení [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Vrací:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Vrací kolekce všech tvarů spojených s uzlem. Pouze pro čtení [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Vrací:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Vrací nebo nastavuje text uzlu. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Vrací nebo nastavuje uzel jako asistenta. Čtení/Zápis boolean.

**Vrací:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Vrací nebo nastavuje uzel jako asistenta. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Vrací úroveň vnoření uzlu. Pouze pro čtení int.

**Vrací:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro odrážku uzlu. Poznámka: může vrátit null pro určité typy rozvržení SmartArt, které neposkytují odrážky pro uzly. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Vrací nebo nastavuje nulově-indexovanou pozici uzlu mezi sourozeneckými uzly. Čtení/Zápis int.

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Vrací nebo nastavuje nulově-indexovanou pozici uzlu mezi sourozeneckými uzly. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Vrací true, pokud je tento uzel v datovém modelu skrytý. Pouze pro čtení boolean.

**Vrací:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Vrací nebo nastavuje typ rozvržení organizačního diagramu spojený s aktuálním uzlem. Čtení/Zápis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Vrací:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Vrací nebo nastavuje typ rozvržení organizačního diagramu spojený s aktuálním uzlem. Čtení/Zápis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Odstranit aktuální uzel.

**Vrací:**
boolean - true if removed succesfully, otherwise false.