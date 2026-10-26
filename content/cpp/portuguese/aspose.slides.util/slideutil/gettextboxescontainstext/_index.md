---
title: GetTextBoxesContainsText()
second_title: Referência da API Aspose.Slides para C++
description: Retorna todos os quadros de texto no slide especificado que contêm o texto fornecido.
type: docs
weight: 66
url: /pt/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) método

Retorna todos os quadros de texto no slide especificado que contêm o texto fornecido.

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | O slide a ser pesquisado. |
| text | [System::String](../../../system/string/) | O texto a ser pesquisado dentro dos quadros de texto. |
| checkPlaceholderText | **bool** | Indica se deve incluir quadros de texto que estão vazios, mas cujo texto de espaço reservado contém o texto de pesquisa. |

### Valor de Retorno

Um array de objetos [ITextFrame](../../../aspose.slides/itextframe/) que contêm o texto especificado.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Classe [String](../../../system/string/)
* Classe [SlideUtil](../)
* Espaço de nomes [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)