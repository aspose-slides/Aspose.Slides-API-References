---
title: IMathParagraphFactory
second_title: Aspose.Slides dla Java – dokumentacja API
description: Umożliwia tworzenie akapitu matematycznego
type: docs
url: /pl/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Umożliwia tworzenie akapitu matematycznego

Dla kompatybilności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Utwórz pusty akapit matematyczny |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Tworzy akapit matematyczny i umieszcza w nim określony blok matematyczny |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

Utwórz pusty akapit matematyczny

**Zwraca:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nowy akapit matematyczny
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

Tworzy akapit matematyczny i umieszcza w nim określony blok matematyczny

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | blok matematyczny do umieszczenia w akapicie |

**Zwraca:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - nowy akapit matematyczny