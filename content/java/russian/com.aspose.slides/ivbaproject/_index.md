---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: Represents VBA project with presentation macros.
type: docs
url: /ru/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Представляет проект VBA с макросами презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Возвращает имя проекта VBA. |
| [getModules()](#getModules--) | Возвращает список всех модулей, содержащихся в проекте VBA. |
| [getReferences()](#getReferences--) | Возвращает список всех ссылок, содержащихся в проекте VBA. |
| [toBinary()](#toBinary--) | Возвращает двоичное представление проекта VBA в виде контейнера OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Указывает, защищён ли VBAProject паролем для просмотра свойств проекта. |
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает имя проекта VBA. Только для чтения String.

**Возвращает:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Возвращает список всех модулей, содержащихся в проекте VBA. Только для чтения [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Возвращает:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Возвращает список всех ссылок, содержащихся в проекте VBA. Только для чтения [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Возвращает:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Возвращает двоичное представление проекта VBA в виде контейнера OLE. Только для чтения byte[].

**Возвращает:**
byte[] - Двоичное представление проекта VBA в виде контейнера OLE
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