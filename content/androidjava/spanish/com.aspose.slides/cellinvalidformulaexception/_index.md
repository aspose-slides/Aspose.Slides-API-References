---
title: CellInvalidFormulaException
second_title: Referencia de la API Java de Aspose.Slides para Android
description: La excepción que se lanza cuando una fórmula calculada no es correcta o no se pudo analizar.
type: docs
url: /es/com.aspose.slides/cellinvalidformulaexception/
---
**Herencia:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

La excepción que se lanza cuando una fórmula calculada no es correcta o no se pudo analizar.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un mensaje de error especificado. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un mensaje de error especificado y una referencia de celda que contiene la fórmula inválida. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getReference()](#getReference--) | Obtiene una referencia de celda que contiene la fórmula inválida. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un mensaje de error especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |
| innerException | java.lang.RuntimeException | La excepción que es la causa de la excepción actual. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Inicializa una nueva instancia de la clase [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) con un mensaje de error especificado y una referencia de celda que contiene la fórmula inválida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |
| reference | java.lang.String | Una cadena que describe una referencia a la excepción interna |

### getReference() {#getReference--}
```
public final String getReference()
```

Obtiene una referencia de celda que contiene la fórmula inválida.

**Devuelve:**
java.lang.String