---
title: CreateMathParagraph()
second_title: Riferimento API Aspose.Slides per C++
description: Crea un paragrafo matemat

ivo vuoto
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathparagraphfactory/createmathparagraph/
---
## IMathParagraphFactory::CreateMathParagraph() metodo


Crea un paragrafo matematico vuoto

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph()=0
```


### Return Value

nuovo paragrafo matematico

## IMathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) metodo


Crea un paragrafo matematico e inserisce il blocco matematico specificato al suo interno

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock)=0
```


### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | blocco matematico da inserire nel paragrafo |

### Return Value

nuovo paragrafo matematico

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathParagraph](../../imathparagraph/)
* Classe [IMathParagraphFactory](../)
* Classe [IMathBlock](../../imathblock/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)