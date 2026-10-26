---
title: set_GridSpacing()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in rutnätsavståndet som ska användas för rutnätet under presentationsdokumentet, i punkter. Skriv float.
type: docs
weight: 105
url: /sv/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) metod


Ställer in rutnätsavståndet som ska användas för rutnätet som ligger till grund för presentationsdokumentet, i punkter. Skriv **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Anmärkningar


Rutnätsavståndsvärdet måste vara ett positivt tal. Det typiska värdeintervallet är från 1 mm (2.8349607 punkter) till 2 tum (144 punkter). 

Följande exempelprogramkod visar hur man ändrar rutnätsavståndet i en PowerPoint-presentation. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [ViewProperties](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)