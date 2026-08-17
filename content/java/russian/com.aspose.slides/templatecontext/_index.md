---
title: TemplateContext
second_title: Справочник API Aspose.Slides для Java
description: Представляет интерфейс объектной модели для шаблонизатора.
type: docs
url: /ru/com.aspose.slides/templatecontext/
---
**Наследование:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Представляет интерфейс объектной модели для шаблонизатора.
## Методы

| Методы | Описание |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Создаёт дочерний контекст шаблона. |
| [getObject()](#getObject--) | Возвращает объект модели. |
| [getOutput()](#getOutput--) | Возвращает коллекцию выходных элементов хост-документа. |
| [getLocal()](#getLocal--) | Возвращает локальное хранилище текущего контекста шаблона. |
| [getGlobal()](#getGlobal--) | Возвращает глобальное хранилище хост-документа. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Создаёт дочерний контекст шаблона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subModel | TSubModel | Объект дочерней модели. |

**Возвращаемое значение:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Новый контекст шаблона с заданной моделью и коллекцией выходных элементов родителя и глобальным хранилищем.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Возвращает объект модели. Только для чтения Object.

**Возвращаемое значение:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Возвращает коллекцию выходных элементов хост-документа. Только для чтения [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Возвращаемое значение:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Возвращает локальное хранилище текущего контекста шаблона. Только для чтения [Storage](../../com.aspose.slides/storage).

**Возвращаемое значение:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Возвращает глобальное хранилище хост-документа. Только для чтения [Storage](../../com.aspose.slides/storage).

**Возвращаемое значение:**
[Storage](../../com.aspose.slides/storage)