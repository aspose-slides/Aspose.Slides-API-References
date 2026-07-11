---
title: VbaProjectFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создавать VBA-проект через COM-интерфейс
type: docs
url: /ru/com.aspose.slides/vbaprojectfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Позволяет создавать VBA-проект через COM-интерфейс
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getInstance()](#getInstance--) | Статический экземпляр фабрики VBA-проекта. |
| [createVbaProject()](#createVbaProject--) | Создает новый VBA-проект. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Читает VBA-проект из OLE-контейнера. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Статический экземпляр фабрики VBA-проекта. Только для чтения [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Возвращаемое значение:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Создает новый VBA-проект.

**Возвращаемое значение:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Новый VBA-проект
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Читает VBA-проект из OLE-контейнера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] |  |

**Возвращаемое значение:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Прочитанный VBA-проект