---
title: IVbaReferenceFactory
second_title: Aspose.Slides для Java API Reference
description: Позволяет создавать ссылки на проекты VBA через COM-интерфейс
type: docs
url: /ru/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Позволяет создавать ссылки на проекты VBA через COM-интерфейс
## Методы

| Метод | Описание |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Создает новую ссылку на библиотеку типов OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Создает новую ссылку на библиотеку типов OLE Automation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя ссылки проекта VBA String |
| libid | java.lang.String | Идентификатор библиотеки типов Automation String |

**Возвращаемое значение:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Новая ссылка на библиотеку типов OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)