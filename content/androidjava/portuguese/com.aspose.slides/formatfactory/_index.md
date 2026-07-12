---
title: FormatFactory
second_title: Aspose.Slides para Android via Referência da API Java
description: Permite criar formatos via interface COM.
type: docs
url: /pt/com.aspose.slides/formatfactory/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFormatFactory](../../com.aspose.slides/iformatfactory)
```
public class FormatFactory implements IFormatFactory
```

Permite criar formatos via interface COM.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [FormatFactory()](#FormatFactory--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getInstance()](#getInstance--) | Instância estática da fábrica de formatos. |
| [createPortionFormat()](#createPortionFormat--) | Cria um novo [IPortionFormat](../../com.aspose.slides/iportionformat). |
| [createParagraphFormat()](#createParagraphFormat--) | Cria um novo [IParagraphFormat](../../com.aspose.slides/iparagraphformat). |
| [createTextFrameFormat()](#createTextFrameFormat--) | Cria um novo [ITextFrameFormat](../../com.aspose.slides/itextframeformat). |
### FormatFactory() {#FormatFactory--}
```
public FormatFactory()
```


### getInstance() {#getInstance--}
```
public static FormatFactory getInstance()
```


Instância estática da fábrica de formatos. Somente leitura [FormatFactory](../../com.aspose.slides/formatfactory).

**Retorna:**
[FormatFactory](../../com.aspose.slides/formatfactory)
### createPortionFormat() {#createPortionFormat--}
```
public final IPortionFormat createPortionFormat()
```


Cria um novo [IPortionFormat](../../com.aspose.slides/iportionformat).

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat) - Novo formato de porção.
### createParagraphFormat() {#createParagraphFormat--}
```
public final IParagraphFormat createParagraphFormat()
```


Cria um novo [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Retorna:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Novo formato de parágrafo.
### createTextFrameFormat() {#createTextFrameFormat--}
```
public final ITextFrameFormat createTextFrameFormat()
```


Cria um novo [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Retorna:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat) - Novo formato de quadro de texto.