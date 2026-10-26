---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет менеджер, который управляет поведением заполнителей, включая заполнитель заголовка для всех типов раздаточных и заметок слайдов.
type: docs
url: /ru/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Представляет менеджер, который управляет поведением заполнителей, включая заполнитель заголовка для всех типов раздаточных и заметок слайдов.

--------------------

Исходное имя интерфейса "IBaseHandoutNotesSlideHeaderFooterManager" усечено до "IBaseHandoutNotesSlideHeaderFooterManag" для совместимости с COM (длина имени типа не должна превышать 39 символов).
## Методы

| Метод | Описание |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Возвращает значение, указывающее, что заполнитель заголовка присутствует. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Изменяет видимость заполнителя заголовка слайда. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Устанавливает текст в заполнитель заголовка слайда. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```

Возвращает значение, указывающее, что заполнитель заголовка присутствует. Читает boolean.

**Возвращает:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```

Изменяет видимость заполнителя заголовка слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true - делает заполнитель заголовка видимым, иначе - скрывает его. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```

Устанавливает текст в заполнитель заголовка слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |