---
title: TemplateContext
second_title: Aspose.Slides for Java API Reference
description: Represents a model object interface for a template engine.
type: docs
weight: 554
url: /java/com.aspose.slides/templatecontext/
---
**Inheritance:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

Represents a model object interface for a template engine.
## Methods

| Method | Description |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Creates a child template context. |
| [getObject()](#getObject--) | Returns the model object. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the host document. |
| [getLocal()](#getLocal--) | Returns local storage of the current template context. |
| [getGlobal()](#getGlobal--) | Returns global storage of the host document. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


Creates a child template context.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| subModel | TSubModel | Child model object. |

**Returns:**
[TemplateContext](../../com.aspose.slides/templatecontext) - New template context with given model and parent's output collection and global storage.
### getObject() {#getObject--}
```
public final TObject getObject()
```


Returns the model object. Read-only Object.

**Returns:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Returns collection of output elements of the host document. Read-only [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**Returns:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


Returns local storage of the current template context. Read-only [Storage](../../com.aspose.slides/storage).

**Returns:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Returns global storage of the host document. Read-only [Storage](../../com.aspose.slides/storage).

**Returns:**
[Storage](../../com.aspose.slides/storage)
