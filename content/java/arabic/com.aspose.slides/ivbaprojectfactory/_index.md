---
title: IVbaProjectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create VBA project via COM interface
type: docs
url: /ar/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

يسمح بإنشاء مشروع VBA عبر واجهة COM
## الأساليب

| Method | Description |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Creates new VBA project. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Reads VBA project from OLE container. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```


Creates new VBA project.

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - New VBA project
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```


Reads VBA project from OLE container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | Ole data byte[] |

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Read VBA project