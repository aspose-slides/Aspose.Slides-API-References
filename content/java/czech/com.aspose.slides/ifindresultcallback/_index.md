---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /cs/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Rozhraní callbacku používané k získání výsledku vyhledávání textu.
## Metody

| Metoda | Popis |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Metoda callbacku, která přijímá data o nalezeném textu. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Metoda callbacku, která přijímá data o nalezeném textu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) ve kterém byl text nalezen. |
| sourceText | java.lang.String | Zdrojový text, ve kterém byl text nalezen. |
| foundText | java.lang.String | Nalezený text. |
| textPosition | int | Pozice nalezeného textu. |