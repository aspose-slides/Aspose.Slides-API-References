---
title: get_ParagraphFormat()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o objeto de formatação para este parágrafo. Somente leitura IParagraphFormat.
type: docs
weight: 14
url: /pt/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() método

Retorna o objeto de formatação para este parágrafo. Somente leitura [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Observações

O objeto de formatação contém os parâmetros de formatação definidos apenas para o parágrafo atual; dados herdados não são aplicados.

Para obter os valores efetivos, incluindo os herdados, use o método [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraphFormat](../../iparagraphformat/)
* Classe [Paragraph](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)