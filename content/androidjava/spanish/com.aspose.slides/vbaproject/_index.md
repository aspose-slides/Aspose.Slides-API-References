---
title: VbaProject
second_title: Aspose.Slides para Android mediante la API de referencia Java
description: Representa un proyecto VBA con macros de presentación.
type: docs
url: /es/com.aspose.slides/vbaproject/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Representa un proyecto VBA con macros de presentación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VbaProject()](#VbaProject--) | Este constructor crea un nuevo proyecto VBA desde cero. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Este constructor carga el proyecto VBA a partir de la representación binaria del contenedor OLE. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Devuelve el nombre del proyecto VBA. |
| [getModules()](#getModules--) | Devuelve la lista de todos los módulos que contiene el proyecto VBA. |
| [getReferences()](#getReferences--) | Devuelve la lista de todas las referencias que contiene el proyecto VBA. |
| [toBinary()](#toBinary--) | Devuelve la representación binaria del proyecto VBA como contenedor OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Este constructor crea un nuevo proyecto VBA desde cero. El proyecto se creará en la página de códigos 1252 Windows Latin 1 (ANSI)

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Este constructor carga el proyecto VBA a partir de la representación binaria del contenedor OLE.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Devuelve el nombre del proyecto VBA. String de solo lectura.

**Devuelve:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Devuelve la lista de todos los módulos que contiene el proyecto VBA. [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection) de solo lectura.

**Devuelve:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Devuelve la lista de todas las referencias que contiene el proyecto VBA. [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection) de solo lectura.

**Devuelve:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Devuelve la representación binaria del proyecto VBA como contenedor OLE

**Devuelve:**
byte[] - Representación binaria del proyecto VBA como contenedor OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Indica si el VBAProject está protegido por una contraseña para ver las propiedades del proyecto. boolean de solo lectura.

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