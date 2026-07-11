---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /ru/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Представляет свойства обычного вида. Обычный вид состоит из трёх областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого.
## Методы

| Метод | Описание |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Указывает, должна ли приложение показывать значки при отображении контурного содержимого в любой из областей содержимого режима обычного вида. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Указывает, должна ли приложение показывать значки при отображении контурного содержимого в любой из областей содержимого режима обычного вида. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Указывает, должна ли вертикальная разделительная полоса переходить в свернутое состояние, когда боковая область достаточно мала. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Указывает, должна ли вертикальная разделительная полоса переходить в свернутое состояние, когда боковая область достаточно мала. |
| [getVerticalBarState()](#getVerticalBarState--) | Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. |
| [getPreferSingleView()](#getPreferSingleView--) | Указывает, предпочитает ли пользователь видеть полноокнообразную единую область содержимого вместо стандартного обычного вида с тремя областями. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Указывает, предпочитает ли пользователь видеть полноокнообразную единую область содержимого вместо стандартного обычного вида с тремя областями. |
| [getRestoredLeft()](#getRestoredLeft--) | Этот элемент задаёт размер боковой области содержимого обычного вида, когда область имеет переменный восстановленный размер (не свернута и не развернута). |
| [getRestoredTop()](#getRestoredTop--) | Этот элемент задаёт размер верхней области слайда обычного вида, когда область имеет переменный восстановленный размер (не свернута и не развернута). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Указывает, должна ли приложение показывать значки при отображении контурного содержимого в любой из областей содержимого режима обычного вида. Чтение/запись boolean.

**Returns:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Указывает, должна ли приложение показывать значки при отображении контурного содержимого в любой из областей содержимого режима обычного вида. Чтение/запись boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Указывает, должна ли вертикальная разделительная полоса переходить в свернутое состояние, когда боковая область достаточно мала. Чтение/запись boolean.

**Returns:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Указывает, должна ли вертикальная разделительная полоса переходить в свернутое состояние, когда боковая область достаточно мала. Чтение/запись boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. Вертикальная разделительная полоса отделяет слайд от боковой области содержимого.

**Returns:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Указывает состояние, в котором должна отображаться вертикальная разделительная полоса. Вертикальная разделительная полоса отделяет слайд от боковой области содержимого.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. Горизонтальная разделительная полоса отделяет слайд от области содержимого под слайдом.

**Returns:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Указывает состояние, в котором должна отображаться горизонтальная разделительная полоса. Горизонтальная разделительная полоса отделяет слайд от области содержимого под слайдом.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Указывает, предпочитает ли пользователь видеть полноокнообразную единую область содержимого вместо стандартного обычного вида с тремя областями. Если включено, приложение может выбрать отображение одной из областей содержимого во всём окне. Чтение/запись boolean.

**Returns:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Указывает, предпочитает ли пользователь видеть полноокнообразную единую область содержимого вместо стандартного обычного вида с тремя областями. Если включено, приложение может выбрать отображение одной из областей содержимого во всём окне. Чтение/запись boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Этот элемент задаёт размер боковой области содержимого обычного вида, когда область имеет переменный восстановленный размер (не свернута и не развернута). Только для чтения [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returns:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Этот элемент задаёт размер верхней области слайда обычного вида, когда область имеет переменный восстановленный размер (не свернута и не развернута). Только для чтения [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Returns:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)