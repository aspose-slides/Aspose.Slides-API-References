---
title: NormalViewProperties
second_title: Справочник API Aspose.Slides для Android через Java
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

Представляет свойства обычного просмотра. Обычный просмотр состоит из трех областей содержимого: самого слайда, боковой области содержимого и нижней области содержимого.

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
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Указывает, должно ли приложение показывать значки при отображении содержания плана в любой из областей содержимого режима обычного просмотра. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Указывает, должно ли приложение показывать значки при отображении содержания плана в любой из областей содержимого режима обычного просмотра. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Указывает, должен ли вертикальный разделитель фиксироваться в минимизированном состоянии, когда боковая область достаточно мала. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Указывает, должен ли вертикальный разделитель фиксироваться в минимизированном состоянии, когда боковая область достаточно мала. |
| [getVerticalBarState()](#getVerticalBarState--) | Указывает состояние, в котором должна отображаться вертикальная полоска-разделитель. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Указывает состояние, в котором должна отображаться вертикальная полоска-разделитель. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Указывает состояние, в котором должна отображаться горизонтальная полоска-разделитель. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Указывает состояние, в котором должна отображаться горизонтальная полоска-разделитель. |
| [getPreferSingleView()](#getPreferSingleView--) | Указывает, предпочитает ли пользователь видеть единую область содержимого во весь экран вместо стандартного обычного просмотра с тремя областями содержимого. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Указывает, предпочитает ли пользователь видеть единую область содержимого во весь экран вместо стандартного обычного просмотра с тремя областями содержимого. |
| [getRestoredLeft()](#getRestoredLeft--) | Этот элемент указывает размеры боковой области содержимого обычного просмотра, когда область имеет переменный восстановленный размер (не минимизирована и не развернута). |
| [getRestoredTop()](#getRestoredTop--) | Этот элемент указывает размеры верхней области слайда обычного просмотра, когда область имеет переменный восстановленный размер (не минимизирована и не развернута). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Указывает, должно ли приложение показывать значки при отображении содержания плана в любой из областей содержимого режима обычного просмотра. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Указывает, должно ли приложение показывать значки при отображении содержания плана в любой из областей содержимого режима обычного просмотра. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Указывает, должен ли вертикальный разделитель фиксироваться в минимизированном состоянии, когда боковая область достаточно мала. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Указывает, должен ли вертикальный разделитель фиксироваться в минимизированном состоянии, когда боковая область достаточно мала. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Указывает состояние, в котором должна отображаться вертикальная полоска-разделитель. Вертикальная полоска-разделитель отделяет слайд от боковой области содержимого.

**Возвращаемое значение:**  
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Указывает состояние, в котором должна отображаться вертикальная полоска-разделитель. Вертикальная полоска-разделитель отделяет слайд от боковой области содержимого.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Указывает состояние, в котором должна отображаться горизонтальная полоска-разделитель. Горизонтальная полоска-разделитель отделяет слайд от области содержимого под слайдом.

**Возвращаемое значение:**  
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Указывает состояние, в котором должна отображаться горизонтальная полоска-разделитель. Горизонтальная полоска-разделитель отделяет слайд от области содержимого под слайдом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Указывает, предпочитает ли пользователь видеть единую область содержимого во весь экран вместо стандартного обычного просмотра с тремя областями содержимого. Если включено, приложение может отобразить одну из областей содержимого на весь экран. Чтение/запись boolean.

**Возвращаемое значение:**  
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Указывает, предпочитает ли пользователь видеть единую область содержимого во весь экран вместо стандартного обычного просмотра с тремя областями содержимого. Если включено, приложение может отобразить одну из областей содержимого на весь экран. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Этот элемент указывает размеры боковой области содержимого обычного просмотра, когда область имеет переменный восстановленный размер (не минимизирована и не развернута). Только для чтения [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Возвращаемое значение:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Этот элемент указывает размеры верхней области слайда обычного просмотра, когда область имеет переменный восстановленный размер (не минимизирована и не развернута). Только для чтения [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Возвращаемое значение:**  
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)