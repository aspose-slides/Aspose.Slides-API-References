---
title: NormalViewProperties
second_title: Aspose.Slides для Java – справка по API
description: Представляет свойства обычного просмотра.
type: docs
url: /ru/com.aspose.slides/normalviewproperties/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Представляет свойства обычного просмотра. Обычный просмотр состоит из трех регионов содержимого: самого слайда, бокового региона содержимого и нижнего региона содержимого.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Создайте объект презентации, представляющий файл презентации
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Указывает, должен ли приложение показывать значки при отображении содержимого структуры в любом из регионов содержимого режима обычного просмотра. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Указывает, должен ли приложение показывать значки при отображении содержимого структуры в любом из регионов содержимого режима обычного просмотра. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Указывает, должен ли вертикальный разделитель переключаться в свернутое состояние, когда боковой регион достаточно мал. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Указывает, должен ли вертикальный разделитель переключаться в свернутое состояние, когда боковой регион достаточно мал. |
| [getVerticalBarState()](#getVerticalBarState--) | Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. |
| [getPreferSingleView()](#getPreferSingleView--) | Указывает, предпочитает ли пользователь видеть одно региональное содержимое во весь экран вместо стандартного обычного просмотра с тремя регионами содержимого. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Указывает, предпочитает ли пользователь видеть одно региональное содержимое во весь экран вместо стандартного обычного просмотра с тремя регионами содержимого. |
| [getRestoredLeft()](#getRestoredLeft--) | Этот элемент определяет размер бокового региона содержимого обычного просмотра, когда регион имеет переменный восстановленный размер (не свернут и не развернут). |
| [getRestoredTop()](#getRestoredTop--) | Этот элемент определяет размер верхнего региона слайда обычного просмотра, когда регион имеет переменный восстановленный размер (не свернут и не развернут). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Указывает, должен ли приложение показывать значки при отображении содержимого структуры в любом из регионов содержимого режима обычного просмотра. Чтение/запись boolean.

**Возвращает:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Указывает, должен ли приложение показывать значки при отображении содержимого структуры в любом из регионов содержимого режима обычного просмотра. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Указывает, должен ли вертикальный разделитель переключаться в свернутое состояние, когда боковой регион достаточно мал. Чтение/запись boolean.

**Возвращает:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Указывает, должен ли вертикальный разделитель переключаться в свернутое состояние, когда боковой регион достаточно мал. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. Вертикальная полоса разделителя отделяет слайд от бокового региона содержимого.

**Возвращает:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Указывает состояние, в котором должна отображаться вертикальная полоса разделителя. Вертикальная полоса разделителя отделяет слайд от бокового региона содержимого.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. Горизонтальная полоса разделителя отделяет слайд от региона содержимого под слайдом.

**Возвращает:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Указывает состояние, в котором должна отображаться горизонтальная полоса разделителя. Горизонтальная полоса разделителя отделяет слайд от региона содержимого под слайдом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Указывает, предпочитает ли пользователь видеть одно региональное содержимое во весь экран вместо стандартного обычного просмотра с тремя регионами содержимого. Если включено, приложение может выбрать отображать один из регионов содержимого во всем окне. Чтение/запись boolean.

**Возвращает:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Указывает, предпочитает ли пользователь видеть одно региональное содержимое во весь экран вместо стандартного обычного просмотра с тремя регионами содержимого. Если включено, приложение может выбрать отображать один из регионов содержимого во всем окне. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Этот элемент определяет размер бокового региона содержимого обычного просмотра, когда регион имеет переменный восстановленный размер (не свернут и не развернут). Только для чтения [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Возвращает:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Этот элемент определяет размер верхнего региона слайда обычного просмотра, когда регион имеет переменный восстановленный размер (не свернут и не развернут). Только для чтения [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Возвращает:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)