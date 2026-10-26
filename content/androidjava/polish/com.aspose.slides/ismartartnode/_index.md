---
title: ISmartArtNode
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Reprezentuje węzeł diagramu SmartArt.
type: docs
url: /pl/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Reprezentuje węzeł diagramu SmartArt.
## Metody

| Metoda | Opis |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Zwraca kolekcje wszystkich węzłów podrzędnych bieżącego węzła. |
| [getShapes()](#getShapes--) | Zwraca kolekcje wszystkich kształtów powiązanych z węzłem. |
| [getTextFrame()](#getTextFrame--) | Zwraca lub ustawia tekst węzła. |
| [isAssistant()](#isAssistant--) | Zwraca lub ustawia węzeł jako asystenta. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Zwraca lub ustawia węzeł jako asystenta. |
| [getLevel()](#getLevel--) | Zwraca poziom zagnieżdżenia węzła. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla wypunktowania węzła. |
| [getPosition()](#getPosition--) | Zwraca lub ustawia pozycję zero-indeksową węzła wśród węzłów siostrzanych. |
| [setPosition(int value)](#setPosition-int-) | Zwraca lub ustawia pozycję zero-indeksową węzła wśród węzłów siostrzanych. |
| [isHidden()](#isHidden--) | Zwraca true, jeśli ten węzeł jest ukrytym węzłem w modelu danych. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. |
| [remove()](#remove--) | Usuwa bieżący węzeł. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Zwraca kolekcje wszystkich węzłów podrzędnych bieżącego węzła. Tylko do odczytu [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Zwraca:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Zwraca kolekcje wszystkich kształtów powiązanych z węzłem. Tylko do odczytu [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Zwraca:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Zwraca lub ustawia tekst węzła. Tylko do odczytu [ITextFrame](../../com.aspose.slides/itextframe).

**Zwraca:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Zwraca lub ustawia węzeł jako asystenta. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Zwraca lub ustawia węzeł jako asystenta. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Zwraca poziom zagnieżdżenia węzła. Tylko do odczytu int.

**Zwraca:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Zwraca obiekt FillFormat, który zawiera właściwości formatowania wypełnienia dla wypunktowania węzła. Uwaga: może zwrócić null dla niektórych typów układu SmartArt, które nie zapewniają wypunktowania dla węzłów. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Zwraca lub ustawia pozycję zero-indeksową węzła wśród węzłów siostrzanych. Odczyt/zapis int.

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Zwraca lub ustawia pozycję zero-indeksową węzła wśród węzłów siostrzanych. Odczyt/zapis int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Zwraca true, jeśli ten węzeł jest ukrytym węzłem w modelu danych. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. Odczyt/zapis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Zwraca:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Zwraca lub ustawia typ układu diagramu organizacyjnego powiązany z bieżącym węzłem. Odczyt/zapis [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Usuwa bieżący węzeł.

**Zwraca:**
boolean - true jeśli usunięto pomyślnie, w przeciwnym razie false.