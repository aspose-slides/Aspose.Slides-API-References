---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Позволяет создавать VBA-проект через интерфейс COM
type: docs
url: /ru/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Позволяет создавать VBA-проект через интерфейс COM

## Методы

| Метод | Описание |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Создаёт новый VBA-проект. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Читает VBA-проект из OLE-контейнера. |

### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Создаёт новый VBA-проект.

**Возвращаемое значение:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - Новый VBA-проект

### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Читает VBA-проект из OLE-контейнера.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | OLE-данные byte[] |

**Возвращаемое значение:**  
[IVbaProject](../../com.aspose.slides/ivbaproject) - Прочитанный VBA-проект