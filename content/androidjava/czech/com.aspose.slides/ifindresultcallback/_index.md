---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Rozhraní zpětného volání použité k získání výsledku vyhledávání textu.
type: docs
url: /cs/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Rozhraní zpětného volání použité k získání výsledku vyhledávání textu.
## Metody

| Metoda | Popis |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Metoda zpětného volání, která přijímá data o nalezeném textu. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Metoda zpětného volání, která přijímá data o nalezeném textu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | [ITextFrame](../../com.aspose.slides/itextframe) ve kterém byl nalezen text. |
| sourceText | java.lang.String | Zdrojový text, ve kterém byl nalezen text. |
| foundText | java.lang.String | Nalezený text. |
| textPosition | int | Pozice nalezeného textu. |