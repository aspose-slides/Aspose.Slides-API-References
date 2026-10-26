---
title: get_HandleRepeatedSpaces()
second_title: Referência da API Aspose.Slides para C++
description: Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação Markdown.
type: docs
weight: 235
url: /pt/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const método


Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Observações


Esta propriedade define se os espaços consecutivos são:
* preservados como caracteres de espaço regulares,
* alternados entre espaços regulares e entidades de espaço não quebrável (**&nbsp;**),
* ou totalmente substituídos (após o primeiro) por **&nbsp;** para preservar o alinhamento visual na saída Markdown.



O valor padrão é [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Veja Também

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)