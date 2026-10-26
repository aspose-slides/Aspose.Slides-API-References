---
title: VbaReferenceFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создавать ссылки на VBA-проекты через COM-интерфейс
type: docs
url: /ru/com.aspose.slides/vbareferencefactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Позволяет создавать ссылки на VBA проекты через COM-интерфейс
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getInstance()](#getInstance--) | Статический экземпляр фабрики ссылок на VBA проекты. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Создаёт новую ссылку на библиотеку типов OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```

Статический экземпляр фабрики ссылок на VBA проекты. Только чтение [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Возвращает:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Создаёт новую ссылку на библиотеку типов OLE Automation.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Возвращает:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Новая ссылка на библиотеку типов OLE Automation