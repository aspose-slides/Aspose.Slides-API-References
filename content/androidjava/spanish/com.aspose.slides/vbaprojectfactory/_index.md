---
title: VbaProjectFactory
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Permite crear un proyecto VBA a través de la interfaz COM
type: docs
url: /es/com.aspose.slides/vbaprojectfactory/
---
**Herencia:**
java.lang.Object

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Permite crear un proyecto VBA a través de la interfaz COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInstance()](#getInstance--) | Instancia estática de la fábrica de proyectos VBA. |
| [createVbaProject()](#createVbaProject--) | Crea un nuevo proyecto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lee el proyecto VBA desde el contenedor OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Instancia estática de la fábrica de proyectos VBA. Solo lectura [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Devuelve:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Crea un nuevo proyecto VBA.

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nuevo proyecto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Lee el proyecto VBA desde el contenedor OLE.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] |  |

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Leer proyecto VBA