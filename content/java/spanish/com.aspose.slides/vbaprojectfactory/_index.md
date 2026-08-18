---
title: VbaProjectFactory
second_title: Referencia de API de Aspose.Slides para Java
description: Permite crear proyectos VBA mediante la interfaz COM
type: docs
url: /es/com.aspose.slides/vbaprojectfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Permite crear proyectos VBA mediante la interfaz COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getInstance()](#getInstance--) | Instancia estática de la fábrica de proyectos VBA. |
| [createVbaProject()](#createVbaProject--) | Crea un nuevo proyecto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lee el proyecto VBA del contenedor OLE. |
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

Lee el proyecto VBA del contenedor OLE.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] |  |

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Lee el proyecto VBA