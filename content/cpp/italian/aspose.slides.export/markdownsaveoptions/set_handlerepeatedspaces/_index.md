---
title: set_HandleRepeatedSpaces()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come gestire i caratteri di spazio regolare ripetuti durante l'esportazione in Markdown.
type: docs
weight: 248
url: /it/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) metodo


Specifica come gestire i caratteri di spazio regolare ripetuti durante l'esportazione in Markdown.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Osservazioni


Questa proprietà definisce se gli spazi consecutivi sono:* mantenuti come caratteri di spazio regolare,
* alternati tra spazi regolari ed entità di spazio non separabile (**&nbsp;**),
* o completamente sostituiti (dopo il primo) con **&nbsp;** per preservare l'allineamento visivo nell'output Markdown.



Il valore predefinito è [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Vedi anche

* Enumerazione [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Classe [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)