---
title: CellInvalidReferenceException
second_title: Referência da API Java do Aspose.Slides para Android
description: A exceção lançada quando uma referência de célula inválida é encontrada.
type: docs
url: /pt/com.aspose.slides/cellinvalidreferenceexception/
---
**Herança:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

A exceção lançada quando uma referência de célula inválida é encontrada.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Inicializa uma nova instância da classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception). |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Inicializa uma nova instância da classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) com uma mensagem de erro especificada. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializa uma nova instância da classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) com uma mensagem de erro especificada e uma referência à exceção interna que é a causa desta exceção. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada e uma referência de célula inválida. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getReference()](#getReference--) | Obtém uma referência de célula inválida. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Inicializa uma nova instância da classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception).

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Inicializa uma nova instância da classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) com uma mensagem de erro especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Inicializa uma nova instância da classe [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) com uma mensagem de erro especificada e uma referência à exceção interna que é a causa desta exceção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |
| innerException | java.lang.RuntimeException | A exceção que é a causa da exceção atual. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada e uma referência de célula inválida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |
| reference | java.lang.String | Uma referência de célula inválida. |

### getReference() {#getReference--}
```
public final String getReference()
```

Obtém uma referência de célula inválida.

**Retorna:**
java.lang.String