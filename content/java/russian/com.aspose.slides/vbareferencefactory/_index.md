---
title: VbaReferenceFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать ссылки на проекты VBA через COM-интерфейс
type: docs
url: /ru/com.aspose.slides/vbareferencefactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Позволяет создавать ссылки на VBA-проекты через COM-интерфейс
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getInstance()](#getInstance--) | Фабрический статический экземпляр ссылок на VBA-проекты. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Создаёт новую ссылку на библиотеку типов OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Фабрический статический экземпляр ссылок на VBA-проекты. Только для чтения [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Возвращаемое значение:**
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

**Возвращаемое значение:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Новая ссылка на библиотеку типов OLE Automation