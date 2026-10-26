---
title: MathParagraphFactory
second_title: Referencia de API de Aspose.Slides para Java
description: Permite crear un párrafo matemático
type: docs
url: /es/com.aspose.slides/mathparagraphfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Permite crear un párrafo matemático

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Crear párrafo matemático vacío |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Crea un párrafo matemático y coloca el bloque matemático especificado en él |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Crear párrafo matemático vacío

**Devuelve:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nuevo párrafo matemático
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Crea un párrafo matemático y coloca el bloque matemático especificado en él

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | bloque matemático que se coloca en el párrafo |

**Devuelve:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nuevo párrafo matemático