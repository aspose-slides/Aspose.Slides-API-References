---
title: CellInvalidFormulaException
second_title: Aspose.Slides para Android via Referência da API Java
description: A exceção lançada quando uma fórmula calculada não está correta ou não foi analisada.
type: docs
url: /pt/com.aspose.slides/cellinvalidformulaexception/
---
**Herança:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

A exceção que é lançada quando uma fórmula calculada não está correta ou não foi analisada.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception). |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) com uma mensagem de erro especificada. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) com uma mensagem de erro especificada e uma referência à exceção interna que é a causa desta exceção. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) com uma mensagem de erro especificada e uma referência de célula que contém a fórmula inválida. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getReference()](#getReference--) | Obtém uma referência de célula que contém a fórmula inválida. |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) com uma mensagem de erro especificada.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) com uma mensagem de erro especificada e uma referência à exceção interna que é a causa desta exceção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |
| innerException | java.lang.RuntimeException | A exceção que é a causa da exceção atual. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Inicializa uma nova instância da classe [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) com uma mensagem de erro especificada e uma referência de célula que contém a fórmula inválida.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| message | java.lang.String | Uma string que descreve o erro. |
| reference | java.lang.String | Uma string que descreve uma referência à exceção interna. |

### getReference() {#getReference--}
```
public final String getReference()
```

Obtém uma referência de célula que contém a fórmula inválida.

**Retorna:**
java.lang.String