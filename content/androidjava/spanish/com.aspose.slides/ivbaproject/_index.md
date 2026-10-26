---
title: IVbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: Representa un proyecto VBA con macros de presentación.
type: docs
url: /es/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Representa un proyecto VBA con macros de presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Devuelve el nombre del proyecto VBA. |
| [getModules()](#getModules--) | Devuelve la lista de todos los módulos que contiene el proyecto VBA. |
| [getReferences()](#getReferences--) | Devuelve la lista de todas las referencias que contiene el proyecto VBA. |
| [toBinary()](#toBinary--) | Devuelve la representación binaria del proyecto VBA como contenedor OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. |
### getName() {#getName--}
```
public abstract String getName()
```

Devuelve el nombre del proyecto VBA. Solo lectura String.

**Devuelve:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Devuelve la lista de todos los módulos que contiene el proyecto VBA. Solo lectura [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Devuelve:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Devuelve la lista de todas las referencias que contiene el proyecto VBA. Solo lectura [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Devuelve:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Devuelve la representación binaria del proyecto VBA como contenedor OLE. Solo lectura byte[].

**Devuelve:**
byte[] - representación binaria del proyecto VBA como contenedor OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. Solo lectura boolean.

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


**Devuelve:**
boolean