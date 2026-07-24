---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie wiederholte reguläre Leerzeichen während des Markdown-Exports behandelt werden sollen.
type: docs
weight: 248
url: /de/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) Methode


Gibt an, wie wiederholte reguläre Leerzeichen während des Markdown-Exports behandelt werden sollen.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Hinweise


Diese Eigenschaft legt fest, ob aufeinanderfolgende Leerzeichen
* als reguläre Leerzeichen erhalten bleiben,
* zwischen regulären Leerzeichen und geschützten Leerzeichen (**&nbsp;**) abwechseln,
* oder vollständig (nach dem ersten) mit **&nbsp;** ersetzt werden, um die visuelle Ausrichtung in der Markdown-Ausgabe beizubehalten.



Der Standardwert ist [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Siehe auch

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Klasse [MarkdownSaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)