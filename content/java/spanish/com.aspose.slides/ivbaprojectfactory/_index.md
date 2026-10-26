---
title: IVbaProjectFactory
second_title: Referencia de API de Aspose.Slides para Java
description: Permite crear un proyecto VBA a través de la interfaz COM
type: docs
url: /es/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Permite crear un proyecto VBA a través de la interfaz COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Crea un nuevo proyecto VBA. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Lee el proyecto VBA del contenedor OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Crea un nuevo proyecto VBA.

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Nuevo proyecto VBA
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Lee el proyecto VBA del contenedor OLE.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Devuelve:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Proyecto VBA leído