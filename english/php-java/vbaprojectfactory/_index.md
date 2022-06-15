---
title: VbaProjectFactory
type: docs
weight: 0
url: /php-java/vbaprojectfactory/
---

# VbaProjectFactory class

 Allows to create VBA project via COM interface
 

## Constructors

| name | description |
| --- | --- |
| [VbaProjectFactory](/slides/php-java/vbaprojectfactory/vbaprojectfactory/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [createVbaProject](/slides/php-java/vbaprojectfactory/createvbaproject/)() | IVbaProject | Creates new VBA project. |
| [getInstance](/slides/php-java/vbaprojectfactory/getinstance/)() | VbaProjectFactory | VBA project factory static instance. Read-only VbaProjectFactory. |
| [readVbaProject](/slides/php-java/vbaprojectfactory/readvbaproject/)(byte[]) | IVbaProject | Reads VBA project from OLE container. |
