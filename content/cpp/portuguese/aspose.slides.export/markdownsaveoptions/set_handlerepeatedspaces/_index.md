---
title: set_HandleRepeatedSpaces()
second_title: Referência da API Aspose.Slides para C++
description: Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown.
type: docs
weight: 248
url: /pt/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) método

Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Observações

Esta propriedade define se os espaços consecutivos são:* preservados como caracteres de espaço regular,
* alternados entre espaços regulares e entidades de espaço não-quebra (**&nbsp;**),
* ou totalmente substituídos (após o primeiro) por **&nbsp;** para preservar o alinhamento visual na saída Markdown.

O valor padrão é [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Ver também

* Enumeração [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Classe [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)