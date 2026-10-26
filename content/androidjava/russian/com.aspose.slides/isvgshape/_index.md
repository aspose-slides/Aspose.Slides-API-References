---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет параметры для SVG-фигуры.
type: docs
url: /ru/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

Представляет параметры для SVG-фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | Sets event handler for the shape |
| [getId()](#getId--) | Sets or gets id for the shape |
| [setId(String value)](#setId-java.lang.String-) | Sets or gets id for the shape |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```

Устанавливает обработчик события для фигуры

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| eventType | int | Тип события. |
| handler | java.lang.String | Javascript-функция для обработки события. Значение null удаляет обработчик. |

### getId() {#getId--}
```
public abstract String getId()
```

Устанавливает или получает id для фигуры

**Возвращаемое значение:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Устанавливает или получает id для фигуры

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |