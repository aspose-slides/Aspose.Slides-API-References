---
title: get_HandleRepeatedSpaces()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come i caratteri di spazio regolari ripetuti devono essere gestiti durante l'esportazione Markdown.
type: docs
weight: 235
url: /it/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const metodo

Specifica come i caratteri di spazio regolari ripetuti devono essere gestiti durante l'esportazione Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Osservazioni

Questa proprietà definisce se gli spazi consecutivi sono:
* conservati come caratteri di spazio regolari,
* alternati tra spazi regolari e entità di spazio non interrotto (**&nbsp;**),
* o completamente sostituiti (dopo il primo) con **&nbsp;** per preservare l'allineamento visivo nell'output Markdown.

Il valore predefinito è [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Vedi anche

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Classe [MarkdownSaveOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)