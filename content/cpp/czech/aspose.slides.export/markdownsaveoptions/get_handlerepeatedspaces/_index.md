---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, jak mají být během exportu do Markdownu zpracovávány opakující se běžné mezerné znaky.
type: docs
weight: 235
url: /cs/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const method

Určuje, jak mají být během exportu do Markdownu zpracovávány opakující se běžné mezery.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Poznámky

Tato vlastnost určuje, zda jsou po sobě jdoucí mezery:
* zachovány jako běžné mezery,
* střídány mezi běžnými mezerami a neoddělitelnými mezerovými entitami (**&nbsp;**),
* nebo plně nahrazeny (po první) **&nbsp;**, aby se zachovala vizuální zarovnání ve výstupu Markdown.

Výchozí hodnota je [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Viz také

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Třída [MarkdownSaveOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)