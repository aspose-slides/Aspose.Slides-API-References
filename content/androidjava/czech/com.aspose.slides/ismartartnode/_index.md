---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje uzel diagramu SmartArt.
type: docs
url: /cs/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Představuje uzel diagramu SmartArt.
## Metody

| Method | Popis |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Vrátí kolekce všech podřízených uzlů aktuálního uzlu. |
| [getShapes()](#getShapes--) | Vrátí kolekce všech tvarů spojených s uzlem. |
| [getTextFrame()](#getTextFrame--) | Vrátí nebo nastaví text uzlu. |
| [isAssistant()](#isAssistant--) | Vrátí nebo nastaví uzel jako asistenta. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Vrátí nebo nastaví uzel jako asistenta. |
| [getLevel()](#getLevel--) | Vrátí úroveň vnoření uzlu. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Vrátí objekt FillFormat, který obsahuje vlastnosti výplně pro odrážku uzlu. |
| [getPosition()](#getPosition--) | Vrátí nebo nastaví nulově indexovanou pozici uzlu mezi sourozeneckými uzly. |
| [setPosition(int value)](#setPosition-int-) | Vrátí nebo nastaví nulově indexovanou pozici uzlu mezi sourozeneckými uzly. |
| [isHidden()](#isHidden--) | Vrátí true, pokud je tento uzel skrytý v datovém modelu. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Vrátí nebo nastaví typ rozložení organizačního diagramu spojený s aktuálním uzlem. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Vrátí nebo nastaví typ rozložení organizačního diagramu spojený s aktuálním uzlem. |
| [remove()](#remove--) | Odstraní aktuální uzel. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Vrátí kolekce všech podřízených uzlů aktuálního uzlu. Pouze ke čtení [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Vrací:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Vrátí kolekce všech tvarů spojených s uzlem. Pouze ke čtení [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Vrací:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Vrátí nebo nastaví text uzlu. Pouze ke čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Vrátí nebo nastaví uzel jako asistenta. Čtení/zápis boolean.

**Vrací:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Vrátí nebo nastaví uzel jako asistenta. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Vrátí úroveň vnoření uzlu. Pouze ke čtení int.

**Vrací:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Vrátí objekt FillFormat, který obsahuje vlastnosti výplně pro odrážku uzlu. Poznámka: může vrátit null pro určité typy rozložení SmartArt, které neposkytují odrážky pro uzly. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Vrátí nebo nastaví nulově indexovanou pozici uzlu mezi sourozeneckými uzly. Čtení/zápis int.

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Vrátí nebo nastaví nulově indexovanou pozici uzlu mezi sourozeneckými uzly. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Vrátí true, pokud je tento uzel skrytý v datovém modelu. Pouze ke čtení boolean.

**Vrací:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Vrátí nebo nastaví typ rozložení organizačního diagramu spojený s aktuálním uzlem. Čtení/zápis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Vrací:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Vrátí nebo nastaví typ rozložení organizačního diagramu spojený s aktuálním uzlem. Čtení/zápis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Odstraní aktuální uzel.

**Vrací:**
boolean – true, pokud byl úspěšně odstraněn, jinak false.