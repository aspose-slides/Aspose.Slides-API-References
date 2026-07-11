---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет узел диаграммы SmartArt.
type: docs
url: /ru/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Представляет узел диаграммы SmartArt.
## Методы

| Метод | Описание |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Возвращает коллекцию всех дочерних узлов текущего узла. |
| [getShapes()](#getShapes--) | Возвращает коллекцию всех фигур, связанных с узлом. |
| [getTextFrame()](#getTextFrame--) | Возвращает или задает текст узла. |
| [isAssistant()](#isAssistant--) | Возвращает или задает узел как помощника. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Возвращает или задает узел как помощника. |
| [getLevel()](#getLevel--) | Возвращает уровень вложенности узла. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Возвращает объект FillFormat, содержащий свойства заливки маркера узла. |
| [getPosition()](#getPosition--) | Возвращает или задает нулевую позицию узла среди соседних узлов. |
| [setPosition(int value)](#setPosition-int-) | Возвращает или задает нулевую позицию узла среди соседних узлов. |
| [isHidden()](#isHidden--) | Возвращает true, если этот узел скрыт в модели данных. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Возвращает или задает тип макета организационной схемы, связанный с текущим узлом. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Возвращает или задает тип макета организационной схемы, связанный с текущим узлом. |
| [remove()](#remove--) | Удаляет текущий узел. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Возвращает коллекцию всех дочерних узлов текущего узла. Только для чтения [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Возвращаемое значение:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Возвращает коллекцию всех фигур, связанных с узлом. Только для чтения [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Возвращаемое значение:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Возвращает или задает текст узла. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Возвращает или задает узел как помощника. Чтение/запись, boolean.

**Возвращаемое значение:**  
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Возвращает или задает узел как помощника. Чтение/запись, boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Возвращает уровень вложенности узла. Только для чтения int.

**Возвращаемое значение:**  
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Возвращает объект FillFormat, содержащий свойства заливки маркера узла. Примечание: может вернуть null для некоторых типов макетов SmartArt, которые не предоставляют маркеры для узлов. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Возвращает или задает нулевую позицию узла среди соседних узлов. Чтение/запись, int.

**Возвращаемое значение:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Возвращает или задает нулевую позицию узла среди соседних узлов. Чтение/запись, int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Возвращает true, если этот узел скрыт в модели данных. Только для чтения boolean.

**Возвращаемое значение:**  
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Возвращает или задает тип макета организационной схемы, связанный с текущим узлом. Чтение/запись [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Возвращаемое значение:**  
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Возвращает или задает тип макета организационной схемы, связанный с текущим узлом. Чтение/запись [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Удаляет текущий узел.

**Возвращаемое значение:**  
boolean - true, если удалено успешно, иначе false.