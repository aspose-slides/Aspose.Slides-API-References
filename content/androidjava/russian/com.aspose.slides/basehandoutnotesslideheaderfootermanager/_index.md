---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, который управляет поведением плейсхолдеров, включая плейсхолдер заголовка для всех типов раздаточных материалов и слайдов заметок.
type: docs
url: /ru/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

Представляет менеджер, который управляет поведением плейсхолдеров, включая плейсхолдер заголовка для всех типов раздаточных материалов и слайдов заметок.
## Методы

| Метод | Описание |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Получает значение, указывающее, что плейсхолдер заголовка присутствует. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Изменяет видимость плейсхолдера заголовка слайда. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Устанавливает текст в плейсхолдер заголовка слайда. |
### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

Получает значение, указывающее, что плейсхолдер заголовка присутствует. Читает boolean.

**Возвращаемое значение:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

Изменяет видимость плейсхолдера заголовка слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает плейсхолдер заголовка видимым, иначе скрывает его. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

Устанавливает текст в плейсхолдер заголовка слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |