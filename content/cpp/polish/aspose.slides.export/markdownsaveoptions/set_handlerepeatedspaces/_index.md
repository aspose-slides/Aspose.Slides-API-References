---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa, jak należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu do formatu Markdown.
type: docs
weight: 248
url: /pl/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) metoda

Określa, jak należy obsługiwać powtarzające się zwykłe znaki spacji podczas eksportu do formatu Markdown.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Uwagi

Ta właściwość określa, czy kolejne spacje są:* zachowywane jako zwykłe znaki spacji,
* zamieniane naprzemiennie między zwykłymi spacjami a znakami niełamiącej spacji (**&nbsp;**),
* lub w pełni zastępowane (po pierwszej) znakiem **&nbsp;**, aby zachować wizualne wyrównanie w wyjściu Markdown.

Domyślna wartość to [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Zobacz także

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)