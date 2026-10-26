---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /it/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Consente di creare un elemento MathematicalText

--------------------

Per la compatibilità COM
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

Crea un elemento vuoto di tipo Mathematical Text

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
| mathSymbol | char | singolo simbolo da utilizzare come valore del testo |

**Restituisce:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Crea un elemento vuoto di tipo Mathematical Text con il valore specificato

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

Crea un elemento vuoto di tipo Mathematical Text con il valore specificato e le impostazioni del formato del testo

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | valore del testo |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | impostazioni del formato del testo |

**Restituisce:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text