---
title: VbaProject
second_title: Aspose.Slides for Android via Java API Reference
description: Represents VBA project with presentation macros.
type: docs
weight: 601
url: /com.aspose.slides/vbaproject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Represents VBA project with presentation macros.
## Constructors

| Constructor | Description |
| --- | --- |
| [VbaProject()](#VbaProject--) | This constructor creates new VBA project from scratch. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | This constructor loads VBA project from binary representation of OLE container. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns the name of the VBA project. |
| [getModules()](#getModules--) | Returns the list of all modules that are contained in the VBA project. |
| [getReferences()](#getReferences--) | Returns the list of all references that are contained in the VBA project. |
| [toBinary()](#toBinary--) | Returns the binary representation of the VBA project as OLE container |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


This constructor creates new VBA project from scratch. Project will be created in 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


This constructor loads VBA project from binary representation of OLE container.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Returns the name of the VBA project. Read-only String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Returns the list of all modules that are contained in the VBA project. Read-only [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Returns the list of all references that are contained in the VBA project. Read-only [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Returns the binary representation of the VBA project as OLE container

**Returns:**
byte[] - Binary representation of the VBA project as OLE container
