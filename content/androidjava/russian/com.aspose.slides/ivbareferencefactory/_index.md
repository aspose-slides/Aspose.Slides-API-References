---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /ru/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Позволяет создавать ссылки на VBA-проекты через COM-интерфейс
## Методы

| Метод | Описание |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Создаёт новую ссылку на библиотеку типов OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Создаёт новую ссылку на библиотеку типов OLE Automation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String | Имя ссылки на VBA-проект String |
| libid | java.lang.String | Идентификатор библиотеки типов Automation String |

**Возвращаемое значение:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Новая ссылка на библиотеку типов OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)