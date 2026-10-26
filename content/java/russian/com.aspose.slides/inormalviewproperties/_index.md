---
title: INormalViewProperties
second_title: Aspose.Slides for Java API Reference
description: Представляет свойства обычного представления.
type: docs
url: /ru/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Представляет свойства обычного представления. Обычное представление состоит из трех областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого.
## Методы

| Метод | Описание |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Указывает, следует ли приложению отображать значки при отображении контурного содержимого в любой из областей содержимого режима обычного представления. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Указывает, следует ли приложению отображать значки при отображении контурного содержимого в любой из областей содержимого режима обычного представления. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Указывает, следует ли вертикальному разделителю переходить в свернутое состояние, когда боковая область достаточно мала. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Указывает, следует ли вертикальному разделителю переходить в свернутое состояние, когда боковая область достаточно мала. |
| [getVerticalBarState()](#getVerticalBarState--) | Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. |
| [getPreferSingleView()](#getPreferSingleView--) | Указывает, предпочитает ли пользователь видеть одноконтентную область во весь экран вместо стандартного обычного представления с тремя областями содержимого. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Указывает, предпочитает ли пользователь видеть одноконтентную область во весь экран вместо стандартного обычного представления с тремя областями содержимого. |
| [getRestoredLeft()](#getRestoredLeft--) | Этот элемент задаёт размер боковой области содержимого обычного представления, когда область имеет переменный восстановленный размер (не свернута и не развернута). |
| [getRestoredTop()](#getRestoredTop--) | Этот элемент задаёт размер верхней области слайда обычного представления, когда область имеет переменный восстановленный размер (не свернута и не развернута). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Указывает, следует ли приложению отображать значки при отображении контурного содержимого в любой из областей содержимого режима обычного представления. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Указывает, следует ли приложению отображать значки при отображении контурного содержимого в любой из областей содержимого режима обычного представления. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Указывает, следует ли вертикальному разделителю переходить в свернутое состояние, когда боковая область достаточно мала. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Указывает, следует ли вертикальному разделителю переходить в свернутое состояние, когда боковая область достаточно мала. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. Вертикальная полоса разделителя отделяет слайд от боковой области содержимого.

**Возвращаемое значение:**  
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. Вертикальная полоса разделителя отделяет слайд от боковой области содержимого.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. Горизонтальная полоса разделителя отделяет слайд от области содержимого под слайдом.

**Возвращаемое значение:**  
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. Горизонтальная полоса разделителя отделяет слайд от области содержимого под слайдом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Указывает, предпочитает ли пользователь видеть одноконтентную область во весь экран вместо стандартного обычного представления с тремя областями содержимого. Если включено, приложение может отобразить одну из областей содержимого во весь экран. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Указывает, предпочитает ли пользователь видеть одноконтентную область во весь экран вместо стандартного обычного представления с тремя областями содержимого. Если включено, приложение может отобразить одну из областей содержимого во весь экран. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Этот элемент задаёт размер боковой области содержимого обычного представления, когда область имеет переменный восстановленный размер (не свернута и не развернута). Только чтение [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Возвращаемое значение:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Этот элемент задаёт размер верхней области слайда обычного представления, когда область имеет переменный восстановленный размер (не свернута и не развернута). Только чтение [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Возвращаемое значение:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)