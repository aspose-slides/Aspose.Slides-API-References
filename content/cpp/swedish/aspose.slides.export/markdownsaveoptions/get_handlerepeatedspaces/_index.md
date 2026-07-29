---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur återkommande vanliga blankstegstecken ska hanteras vid Markdown-export.
type: docs
weight: 235
url: /sv/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const metod

Anger hur återkommande vanliga blankstegstecken ska hanteras vid Markdown-export.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Anmärkningar

Denna egenskap definierar om på varandra följande mellanslag är:* bevaras som vanliga blankstegstecken,
* växlas mellan vanliga blanksteg och icke-brytande mellanslagstecken (**&nbsp;**),
* eller helt ersätts (efter det första) med **&nbsp;** för att bevara visuell justering i Markdown-utdata.

Det förvalda värdet är [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Se också

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Klass [MarkdownSaveOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)