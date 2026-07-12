---
title: CellInvalidReferenceException
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: La excepción que se lanza cuando se encuentra una referencia de celda no válida.
type: docs
url: /es/com.aspose.slides/cellinvalidreferenceexception/
---
**Herencia:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

La excepción que se lanza cuando se encuentra una referencia de celda no válida.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inicializa una nueva instancia de la clase [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inicializa una nueva instancia de la clase [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un mensaje de error especificado. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializa una nueva instancia de la clase [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado y una referencia de celda no válida. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getReference()](#getReference--) | Obtiene una referencia de celda no válida. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```


Inicializa una nueva instancia de la clase [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```


Inicializa una nueva instancia de la clase [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un mensaje de error especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```


Inicializa una nueva instancia de la clase [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |
| innerException | java.lang.RuntimeException | La excepción que es la causa de la excepción actual. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```


Inicializa una nueva instancia de la clase [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) con un mensaje de error especificado y una referencia de celda no válida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| message | java.lang.String | Una cadena que describe el error. |
| reference | java.lang.String | Una referencia de celda no válida. |

### getReference() {#getReference--}
```
public final String getReference()
```


Obtiene una referencia de celda no válida.

**Devuelve:**
java.lang.String