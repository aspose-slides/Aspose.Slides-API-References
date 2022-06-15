---
title: TemplateContext
type: docs
weight: 0
url: /php-java/templatecontext/
---

# TemplateContext class

 Represents a model object interface for a template engine.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getGlobal](/php-java/templatecontext/getglobal/)() | Storage | Returns global storage of the host document. Read-only Storage. |
| [getLocal](/php-java/templatecontext/getlocal/)() | Storage | Returns local storage of the current template context. Read-only Storage. |
| [getObject](/php-java/templatecontext/getobject/)() | TObject | Returns the model object. Read-only Object. |
| [getOutput](/php-java/templatecontext/getoutput/)() | Output | Returns collection of output elements of the host document. Read-only Output( #getOutput). |
| [subModel](/php-java/templatecontext/submodel/)(TSubModel) | TemplateContext | Creates a child template context. |
