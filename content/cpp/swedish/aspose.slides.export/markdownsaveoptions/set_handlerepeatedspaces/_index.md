---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur upprepade vanliga mellanslagstecken ska hanteras vid Markdown-export.
type: docs
weight: 248
url: /sv/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) metod


Specificerar hur upprepade vanliga mellanslagstecken ska hanteras under Markdown-export.

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## Anmärkningar


Denna egenskap definierar om på varandra följande mellanslag är:
* bevarade som vanliga mellanslagstecken,
* alternerande mellan vanliga mellanslag och icke-brytande mellanslag-entiteter (**&nbsp;**),
* eller helt ersatta (efter den första) med **&nbsp;** för att bevara visuell justering i Markdown-utdata.



Standardvärdet är [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Se också

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Klass [MarkdownSaveOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)