---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare un elemento MathematicalText
type: docs
url: /it/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Consente di creare un elemento MathematicalText

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Crea un elemento di testo matematico vuoto

**Restituisce:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Crea un elemento di testo matematico con il valore specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathSymbol | char | singolo simbolo da usare come valore di testo |

**Restituisce:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Crea un elemento di testo matematico vuoto con il valore specificato

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | valore del testo |

**Restituisce:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Crea un elemento di testo matematico vuoto con il valore specificato e le proprietà di formattazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | valore del testo |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | impostazioni del formato del testo |

**Restituisce:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text