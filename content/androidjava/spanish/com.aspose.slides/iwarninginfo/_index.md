---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /es/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Representa una interfaz base para todas las advertencias.
## Métodos

| Método | Descripción |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Si receiver no es nulo finaliza la advertencia a un receiver especificado y lanza AbortRequestedException si receiver decidió abortar una operación. |
| [getWarningType()](#getWarningType--) | Devuelve un tipo de advertencia. |
| [getDescription()](#getDescription--) | Devuelve una descripción legible por humanos de esta advertencia. |

### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Si receiver no es nulo finaliza la advertencia a un receiver especificado y lanza AbortRequestedException si receiver decidió abortar una operación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Objeto Receiver [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Devuelve un tipo de advertencia. Solo lectura [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Devuelve:**  
int

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Devuelve una descripción legible por humanos de esta advertencia. Solo lectura String.

**Devuelve:**  
java.lang.String