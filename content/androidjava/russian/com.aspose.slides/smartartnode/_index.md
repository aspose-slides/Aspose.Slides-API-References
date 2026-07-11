---
title: SmartArtNode
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет узел объекта SmartArt
type: docs
url: /ru/com.aspose.slides/smartartnode/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Представляет узел объекта SmartArt
## Методы

| Метод | Описание |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Возвращает коллекцию всех дочерних узлов текущего узла. |
| [getShapes()](#getShapes--) | Возвращает коллекцию всех фигур, связанных с узлом. |
| [getTextFrame()](#getTextFrame--) | Возвращает текстовый кадр узла. |
| [isAssistant()](#isAssistant--) | Возвращает или устанавливает узел как помощника. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Возвращает или устанавливает узел как помощника. |
| [getLevel()](#getLevel--) | Возвращает уровень вложенности узла. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Возвращает объект FillFormat, содержащий свойства заливки для маркера узла. |
| [getPosition()](#getPosition--) | Возвращает или устанавливает позицию узла среди одноуровневых узлов, начиная с нуля. |
| [setPosition(int value)](#setPosition-int-) | Возвращает или устанавливает позицию узла среди одноуровневых узлов, начиная с нуля. |
| [isHidden()](#isHidden--) | Возвращает true, если этот узел является скрытым узлом в модели данных. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Возвращает или устанавливает тип макета организационной схемы, связанный с текущим узлом. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Возвращает или устанавливает тип макета организационной схемы, связанный с текущим узлом. |
| [remove()](#remove--) | Удалить текущий узел. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Возвращает коллекцию всех дочерних узлов текущего узла. Только для чтения [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Возвращаемое значение:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Возвращает коллекцию всех фигур, связанных с узлом. Только для чтения [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Возвращаемое значение:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Возвращает текстовый кадр узла. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Возвращает или устанавливает узел как помощника. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Возвращает или устанавливает узел как помощника. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Возвращает уровень вложенности узла. Только для чтения int.

**Возвращаемое значение:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Возвращает объект FillFormat, содержащий свойства заливки для маркера узла. Примечание: может возвращать null для некоторых типов макета SmartArt, которые не предоставляют маркеры для узлов. Только для чтения [IFillFormat](../../com.aspose.slides/ifillformat).

**Возвращаемое значение:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Возвращает или устанавливает позицию узла среди одноуровневых узлов, начиная с нуля. Чтение/запись int.

**Возвращаемое значение:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Возвращает или устанавливает позицию узла среди одноуровневых узлов, начиная с нуля. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Возвращает true, если этот узел является скрытым узлом в модели данных. Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Возвращает или устанавливает тип макета организационной схемы, связанный с текущим узлом. Чтение/запись [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Возвращаемое значение:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Возвращает или устанавливает тип макета организационной схемы, связанный с текущим узлом. Чтение/запись [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Удалить текущий узел.

**Возвращаемое значение:**
boolean - true, если удалено успешно, иначе false