---
title: VbaProject
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет проект VBA с макросами презентации.
type: docs
url: /ru/com.aspose.slides/vbaproject/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Представляет проект VBA с макросами презентации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VbaProject()](#VbaProject--) | Этот конструктор создает новый проект VBA с нуля. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Этот конструктор загружает проект VBA из бинарного представления контейнера OLE. |
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Возвращает имя проекта VBA. |
| [getModules()](#getModules--) | Возвращает список всех модулей, содержащихся в проекте VBA. |
| [getReferences()](#getReferences--) | Возвращает список всех ссылок, содержащихся в проекте VBA. |
| [toBinary()](#toBinary--) | Возвращает бинарное представление проекта VBA как контейнер OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Этот конструктор создает новый проект VBA с нуля. Проект будет создан в 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Этот конструктор загружает проект VBA из бинарного представления контейнера OLE.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Возвращает имя проекта VBA. Только для чтения String.

**Возвращаемое значение:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Возвращает список всех модулей, содержащихся в проекте VBA. Только для чтения [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Возвращаемое значение:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Возвращает список всех ссылок, содержащихся в проекте VBA. Только для чтения [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Возвращаемое значение:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Возвращает бинарное представление проекта VBA как контейнер OLE

**Возвращаемое значение:**
byte[] - Бинарное представление проекта VBA как контейнер OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. Только для чтения  boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращаемое значение:**
boolean