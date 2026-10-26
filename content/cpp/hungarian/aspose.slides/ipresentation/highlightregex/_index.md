---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API Referenciája
description: Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.
type: docs
weight: 469
url: /hu/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metódus


Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A reguláris kifejezés [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) a kiemelendő karakterláncokhoz. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásáért felelős visszahívási objektum. |
## Megjegyzés



Az alábbi kódmintában látható, hogyan lehet kiemelni a szöveget egy PowerPoint [Presentation](../../presentation/)-ban reguláris kifejezés segítségével. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// 10 vagy több karakterből álló összes szó kiemelése
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Regex](../../../system.text.regularexpressions/regex/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [IPresentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)