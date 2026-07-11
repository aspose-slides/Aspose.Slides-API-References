---
title: IVbaProjectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Позволяет создавать VBA-проект через COM-интерфейс
type: docs
url: /ru/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Позволяет создавать VBA-проект через COM-интерфейс
## Методы

| Метод | Описание |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Создает новый VBA-проект. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Считывает VBA-проект из OLE-контейнера. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Создает новый VBA-проект.

**Возвращаемое значение:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Новый VBA-проект
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Считывает VBA-проект из OLE-контейнера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Ole-данные byte[] |

**Возвращаемое значение:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Прочитанный VBA-проект