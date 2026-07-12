---
title: CellCircularReferenceException
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: La excepción que se lanza cuando se detectan una o más referencias circulares donde una fórmula hace referencia a su propia celda, ya sea directa o indirectamente.
type: docs
url: /es/com.aspose.slides/cellcircularreferenceexception/
---
**Herencia:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

La excepción que se lanza cuando se detecta una o más referencias circulares donde una fórmula hace referencia a su propia celda, ya sea directa o indirectamente.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado y una referencia circular a una celda. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getReference()](#getReference--) | Obtiene una referencia circular a una celda. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |
| innerException | java.lang.RuntimeException | La excepción que es la causa de la excepción actual. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado y una referencia circular a una celda.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |
| reference | java.lang.String | Una referencia circular a una celda. |

### getReference() {#getReference--}
```
public final String getReference()
```

Obtiene una referencia circular a una celda.

**Devuelve:**
java.lang.String