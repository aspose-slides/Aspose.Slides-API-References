---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Interface de callback usada para obter o resultado da pesquisa de texto.
type: docs
url: /pt/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Interface de callback usada para obter o resultado da pesquisa de texto.
## Métodos

| Método | Descrição |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Método de callback que recebe dados sobre o texto encontrado. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Método de callback que recebe dados sobre o texto encontrado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | O [ITextFrame](../../com.aspose.slides/itextframe) onde o texto foi encontrado. |
| sourceText | java.lang.String | O texto de origem onde o texto foi encontrado. |
| foundText | java.lang.String | O texto encontrado. |
| textPosition | int | A posição do texto encontrado. |