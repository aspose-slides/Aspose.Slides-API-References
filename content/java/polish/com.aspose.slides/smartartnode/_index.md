---
title: SmartArtNode
second_title: Referencja API Aspose.Slides dla Javy
description: Reprezentuje węzeł obiektu SmartArt
type: docs
url: /pl/com.aspose.slides/smartartnode/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Reprezentuje węzeł obiektu SmartArt
## Metody

| Metoda | Opis |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Zwraca kolekcje wszystkich węzłów potomnych bieżącego węzła. |
| [getShapes()](#getShapes--) | Zwraca kolekcje wszystkich kształtów powiązanych z węzłem. |
| [getTextFrame()](#getTextFrame--) | Zwraca ramkę tekstową węzła. |
| [isAssistant()](#isAssistant--) | Zwraca lub ustawia węzeł jako asystenta. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Zwraca lub ustawia węzeł jako asystenta. |
| [getLevel()](#getLevel--) | Zwraca poziom zagnieżdżenia węzła. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla punktora węzła. |
| [getPosition()](#getPosition--) | Zwraca lub ustawia pozycję zerową węzła wśród węzłów rodzeństwa. |
| [setPosition(int value)](#setPosition-int-) | Zwraca lub ustawia pozycję zerową węzła wśród węzłów rodzeństwa. |
| [isHidden()](#isHidden--) | Zwraca true, jeśli ten węzeł jest ukrytym węzłem w modelu danych. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. |
| [remove()](#remove--) | Usuwa bieżący węzeł. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


Zwraca kolekcje wszystkich węzłów potomnych bieżącego węzła. Tylko do odczytu [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Zwraca:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


Zwraca kolekcje wszystkich kształtów powiązanych z węzłem. Tylko do odczytu [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Zwraca:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Zwraca ramkę tekstową węzła. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


Zwraca lub ustawia węzeł jako asystenta. Do odczytu i zapisu boolean.

**Zwraca:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


Zwraca lub ustawia węzeł jako asystenta. Do odczytu i zapisu boolean.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```


Zwraca poziom zagnieżdżenia węzła. Tylko do odczytu int.

**Zwraca:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla punktora węzła. Uwaga: może zwrócić null dla niektórych typów układu SmartArt, które nie zapewniają punktorów dla węzłów. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Zwraca lub ustawia pozycję zerową węzła wśród węzłów rodzeństwa. Do odczytu i zapisu int.

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Zwraca lub ustawia pozycję zerową węzła wśród węzłów rodzeństwa. Do odczytu i zapisu int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Zwraca true, jeśli ten węzeł jest ukrytym węzłem w modelu danych. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. Do odczytu i zapisu [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Zwraca:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. Do odczytu i zapisu [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```


Usuwa bieżący węzeł.

**Zwraca:**
boolean - true, jeśli usunięto pomyślnie, w przeciwnym razie false