---
title: CellCircularReferenceException
second_title: Referência da API Java do Aspose.Slides para Android
description: A exceção lançada quando uma ou mais referências circulares são detectadas onde uma fórmula se refere à sua própria célula, direta ou indiretamente.
type: docs
url: /pt/com.aspose.slides/cellcircularreferenceexception/
---
**Herança:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

A exceção lançada quando uma ou mais referências circulares são detectadas onde uma fórmula se refere à sua própria célula, direta ou indirectamente.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception). |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada e uma referência para a exceção interna que é a causa desta exceção. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada e referência de célula circular. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getReference()](#getReference--) | Obtém uma referência de célula circular. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```


Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```


Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```


Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada e uma referência para a exceção interna que é a causa desta exceção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |
| innerException | java.lang.RuntimeException | A exceção que é a causa da exceção atual. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```


Inicializa uma nova instância da classe [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) com uma mensagem de erro especificada e referência de célula circular.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |
| reference | java.lang.String | Uma referência de célula circular. |

### getReference() {#getReference--}
```
public final String getReference()
```


Obtém uma referência de célula circular.

**Retorna:**
java.lang.String