---
title: IBaseHandoutNotesSlideHeaderFooterManag
second_title: Справочник API Aspose.Slides для Java
description: Представляет менеджер, который реализует поведение заполнителей, включая заголовочный заполнитель для всех типов раздаточных и заметочных слайдов.
type: docs
url: /ru/com.aspose.slides/ibasehandoutnotesslideheaderfootermanag/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IBaseHandoutNotesSlideHeaderFooterManag extends IBaseSlideHeaderFooterManager
```

Представляет менеджер, который содержит поведение заполнителей, включая заголовочный заполнитель для всех типов раздаточных и заметочных слайдов.

--------------------

Original interface name "IBaseHandoutNotesSlideHeaderFooterManager" is trancuted to "IBaseHandoutNotesSlideHeaderFooterManag" for COM compatibility (type name length must be not more than 39).
## Методы

| Метод | Описание |
| --- | --- |
| [isHeaderVisible()](#isHeaderVisible--) | Получает значение, указывающее, что заголовочный заполнитель присутствует. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | Изменяет видимость заголовочного заполнителя слайда. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | Устанавливает текст в заголовочный заполнитель слайда. |
### isHeaderVisible() {#isHeaderVisible--}
```
public abstract boolean isHeaderVisible()
```


Получает значение, указывающее, что заголовочный заполнитель присутствует. Читает булево значение.

**Возвращаемое значение:**
boolean
### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public abstract void setHeaderVisibility(boolean isVisible)
```


Изменяет видимость заголовочного заполнителя слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| isVisible | boolean | true — делает заголовочный заполнитель видимым, иначе — скрывает его. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public abstract void setHeaderText(String text)
```


Устанавливает текст в заголовочный заполнитель слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для установки. |