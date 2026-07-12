---
title: IWarningCallback
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Interfaz para clases que reciben advertencias
type: docs
url: /es/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Interfaz para clases que reciben advertencias
## Métodos

| Método | Descripción |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Método de devolución de llamada que recibe una advertencia y decide si la operación debe abortarse. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Método de devolución de llamada que recibe una advertencia y decide si la operación debe abortarse.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | Advertencia a procesar. |

**Devuelve:**
int - Decisión de aborto [ReturnAction](../../com.aspose.slides/returnaction).