---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, w jaki sposób powtarzające się zwykłe znaki spacji powinny być obsługiwane podczas eksportu do formatu Markdown.
type: docs
weight: 235
url: /pl/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const metoda


Określa, w jaki sposób należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Uwagi


Ta właściwość określa, czy kolejne spacje są:
* zachowywane jako zwykłe znaki spacji,
* zamieniane na naprzemiennie zwykłe spacje i encje niełamliwych spacji (**&nbsp;**),
* czy też w pełni zastępowane (po pierwszej) **&nbsp;**, aby zachować wizualne wyrównanie w wyjściu Markdown.



Domyślna wartość to [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Zobacz także

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Klasa [MarkdownSaveOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)