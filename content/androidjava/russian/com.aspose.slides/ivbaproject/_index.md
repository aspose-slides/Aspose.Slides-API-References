---
title: IVbaProject
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет VBA-проект с макросами презентации.
type: docs
url: /ru/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Представляет VBA-проект с макросами презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Возвращает имя VBA-проекта. |
| [getModules()](#getModules--) | Возвращает список всех модулей, содержащихся в VBA-проекте. |
| [getReferences()](#getReferences--) | Возвращает список всех ссылок, содержащихся в VBA-проекте. |
| [toBinary()](#toBinary--) | Возвращает двоичное представление VBA-проекта в виде контейнера OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. |
### getName() {#getName--}
```
public abstract String getName()
```


Возвращает имя VBA-проекта. Только для чтения String.

**Возвращает:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Возвращает список всех модулей, содержащихся в VBA-проекте. Только для чтения [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Возвращает:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Возвращает список всех ссылок, содержащихся в VBA-проекте. Только для чтения [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Возвращает:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Возвращает двоичное представление VBA-проекта в виде контейнера OLE. Только для чтения byte[].

**Возвращает:**
byte[] - Binary representation of the VBA project as OLE container
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. Только для чтения boolean.

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


**Возвращает:**
boolean