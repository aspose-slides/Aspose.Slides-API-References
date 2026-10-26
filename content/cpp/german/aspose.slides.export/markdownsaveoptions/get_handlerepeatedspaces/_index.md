---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie wiederholte reguläre Leerzeichen beim Markdown-Export behandelt werden sollen.
type: docs
weight: 235
url: /de/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const Methode

Gibt an, wie wiederholte normale Leerzeichen beim Markdown-Export behandelt werden sollen.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Hinweise

Diese Eigenschaft definiert, ob aufeinanderfolgende Leerzeichen
* beibehalten als normale Leerzeichen,
* abwechselnd zwischen normalen Leerzeichen und nicht-brechenden Leerzeichen-Entitäten (**&nbsp;**),
* oder vollständig (nach dem ersten) durch **&nbsp;** ersetzt, um die visuelle Ausrichtung in der Markdown-Ausgabe beizubehalten.

Der Standardwert ist [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Siehe auch

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Klasse [MarkdownSaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)