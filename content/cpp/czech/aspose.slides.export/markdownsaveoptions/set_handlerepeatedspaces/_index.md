---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, jak mají být při exportu do Markdownu zpracovávány opakované běžné mezerné znaky.
type: docs
weight: 248
url: /cs/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) metoda


Určuje, jak mají být při exportu do Markdownu zpracovávány opakované běžné mezerné znaky.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Poznámky


Tato vlastnost určuje, zda po sobě jdoucí mezery jsou:* zachovány jako běžné mezerné znaky,
* střídány mezi běžnými mezerami a entitami nezlomitelné mezery (**&nbsp;**),
* nebo zcela nahrazeny (po první) znakem **&nbsp;**, aby se zachovala vizuální zarovnání ve výstupu Markdownu.



Výchozí hodnota je [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Viz také

* Výčet [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Třída [MarkdownSaveOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)