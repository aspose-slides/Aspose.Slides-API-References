---
title: IVbaProject
second_title: Aspose.Slides for Java API Reference
description: Represents VBA project with presentation macros.
type: docs
weight: 1099
url: /java/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Represents VBA project with presentation macros.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Returns the name of the VBA project. |
| [getModules()](#getModules--) | Returns the list of all modules that are contained in the VBA project. |
| [getReferences()](#getReferences--) | Returns the list of all references that are contained in the VBA project. |
| [toBinary()](#toBinary--) | Returns the binary representation of the VBA project as OLE container. |
### getName() {#getName--}
```
public abstract String getName()
```


Returns the name of the VBA project. Read-only String.

**Returns:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```


Returns the list of all modules that are contained in the VBA project. Read-only [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Returns:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```


Returns the list of all references that are contained in the VBA project. Read-only [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Returns:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```


Returns the binary representation of the VBA project as OLE container. Read-only byte[].

**Returns:**
byte[] - Binary representation of the VBA project as OLE container
