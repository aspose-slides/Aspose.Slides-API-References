---
title: SmartArtNode
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje uzel objektu SmartArt
type: docs
url: /cs/com.aspose.slides/smartartnode/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Reprezentuje uzel objektu SmartArt
## Metody

| Metoda | Popis |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Vrací kolekci všech podřízených uzlů aktuálního uzlu. |
| [getShapes()](#getShapes--) | Vrací kolekci všech tvarů spojených s uzlem. |
| [getTextFrame()](#getTextFrame--) | Vrací textový rámec uzlu. |
| [isAssistant()](#isAssistant--) | Vrací nebo nastavuje uzel jako asistenta. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Vrací nebo nastavuje uzel jako asistenta. |
| [getLevel()](#getLevel--) | Vrací úroveň vnoření uzlu. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro odrážku uzlu. |
| [getPosition()](#getPosition--) | Vrací nebo nastavuje nulovou (indexovou) pozici uzlu mezi sourozeneckými uzly. |
| [setPosition(int value)](#setPosition-int-) | Vrací nebo nastavuje nulovou (indexovou) pozici uzlu mezi sourozeneckými uzly. |
| [isHidden()](#isHidden--) | Vrací true, pokud je tento uzel skrytý v datovém modelu. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Vrací nebo nastavuje typ rozložení organizačního diagramu spojený s aktuálním uzlem. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Vrací nebo nastavuje typ rozložení organizačního diagramu spojený s aktuálním uzlem. |
| [remove()](#remove--) | Odstraní aktuální uzel. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


Vrací kolekci všech podřízených uzlů aktuálního uzlu. Pouze pro čtení [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Vrací:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


Vrací kolekci všech tvarů spojených s uzlem. Pouze pro čtení [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Vrací:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Vrací textový rámec uzlu. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


Vrací nebo nastavuje uzel jako asistenta. Čtení/Zápis boolean.

**Vrací:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


Vrací nebo nastavuje uzel jako asistenta. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```


Vrací úroveň vnoření uzlu. Pouze pro čtení int.

**Vrací:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro odrážku uzlu. Poznámka: může vrátit null pro určité typy rozložení SmartArt, které neposkytují odrážky pro uzly. Pouze pro čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Vrací nebo nastavuje nulovou (indexovou) pozici uzlu mezi sourozeneckými uzly. Čtení/Zápis  int .

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Vrací nebo nastavuje nulovou (indexovou) pozici uzlu mezi sourozeneckými uzly. Čtení/Zápis  int .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Vrací true, pokud je tento uzel skrytý v datovém modelu. Pouze pro čtení boolean.

**Vrací:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


Vrací nebo nastavuje typ rozložení organizačního diagramu spojený s aktuálním uzlem. Čtení/Zápis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Vrací:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


Vrací nebo nastavuje typ rozložení organizačního diagramu spojený s aktuálním uzlem. Čtení/Zápis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```


Odstraní aktuální uzel.

**Vrací:**
boolean - true pokud byl úspěšně odstraněn, jinak false