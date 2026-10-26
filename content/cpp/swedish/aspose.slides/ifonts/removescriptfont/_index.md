---
title: RemoveScriptFont()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort teckensnittsinställningen som är associerad med en specifik skripttagg från temats teckensnittssamling.
type: docs
weight: 118
url: /sv/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) metod


Tar bort teckensnittsinställningen som är associerad med en specifik skripttagg från temats teckensnittssamling.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 skriptkoden vars teckensnittinställning ska tas bort. |
## Anmärkningar



Det här exemplet visar hur man tar bort teckensnittsmappningen för det hebraiska skriptet: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Se även

* Klass [String](../../../system/string/)
* Klass [IFonts](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)