---
title: BrowsedByIndividual
second_title: Aspose.Slides для Android через справочник Java API
description: Окно просмотра отдельным пользователем
type: docs
url: /ru/com.aspose.slides/browsedbyindividual/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Просмотр отдельным (окно)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Инициализирует новый экземпляр класса BrowsedByIndividual. |
## Методы

| Метод | Описание |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Показать полосу прокрутки в окне |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Показать полосу прокрутки в окне |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

Инициализирует новый экземпляр класса BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```

Показать полосу прокрутки в окне

**Возвращаемое значение:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

Показать полосу прокрутки в окне

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |