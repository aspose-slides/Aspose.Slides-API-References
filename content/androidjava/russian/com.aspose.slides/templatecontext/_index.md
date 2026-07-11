---
title: TemplateContext
second_title: Aspose.Slides для Android через Java API справка
description: Представляет интерфейс объектной модели для движка шаблонов.
type: docs
url: /ru/com.aspose.slides/templatecontext/
---
**Наследование:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Представляет интерфейс объектной модели для движка шаблонов.
## Методы

| Метод | Описание |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Создает дочерний контекст шаблона. |
| [getObject()](#getObject--) | Возвращает объект модели. |
| [getOutput()](#getOutput--) | Возвращает коллекцию элементов вывода из документа-хоста. |
| [getLocal()](#getLocal--) | Возвращает локальное хранилище текущего контекста шаблона. |
| [getGlobal()](#getGlobal--) | Возвращает глобальное хранилище документа-хоста. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

Создает дочерний контекст шаблона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subModel | TSubModel | Объект дочерней модели. |

**Возвращает:**
[TemplateContext](../../com.aspose.slides/templatecontext) - Новый контекст шаблона с заданной моделью и коллекцией вывода родителя и глобальным хранилищем.
### getObject() {#getObject--}
```
public final TObject getObject()
```

Возвращает объект модели. Только для чтения Object.

**Возвращает:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Возвращает коллекцию элементов вывода из документа-хоста. Только для чтения [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Возвращает:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

Возвращает локальное хранилище текущего контекста шаблона. Только для чтения [Storage](../../com.aspose.slides/storage).

**Возвращает:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Возвращает глобальное хранилище документа-хоста. Только для чтения [Storage](../../com.aspose.slides/storage).

**Возвращает:**
[Storage](../../com.aspose.slides/storage)