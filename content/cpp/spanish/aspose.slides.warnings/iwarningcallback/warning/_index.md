---
title: Warning()
second_title: Referencia de la API de Aspose.Slides para C++
description: Método de devolución de llamada que recibe una advertencia y decide si la operación debe abortarse.
type: docs
weight: 1
url: /es/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) método

Método de devolución de llamada que recibe una advertencia y decide si la operación debe abortarse.

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | Advertencia a procesar. |

### Valor devuelto

Decisión de aborto [ReturnAction](../../returnaction/).

## Ver también

* Enumeración [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IWarningInfo](../../iwarninginfo/)
* Clase [IWarningCallback](../)
* Espacio de nombres [Aspose::Slides::Warnings](../../)
* Biblioteca [Aspose.Slides](../../../)