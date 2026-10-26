---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja a Summary Zoom Section objektumot a gyűjteményből.
type: docs
weight: 79
url: /hu/aspose.slides/summaryzoomsectioncollection/removesummaryzoomsection/
---
## SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metódus


Eltávolítja a Summary Zoom [Section](../../section/) objektumot a gyűjteményből.

```cpp
void Aspose::Slides::SummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) amelyhez a Summary Zoom [Section](../../section/) elemet kell eltávolítani [ISection](../../isection/). |
## Megjegyzések



A példában bemutatjuk, hogyan lehet index alapján lekérni a Summary Zoom [Section](../../section/) elemet: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(1)->get_Shapes();

auto zoomFrame = System::ExplicitCast<ISummaryZoomFrame>(shapes->idx_get(0));
auto collection = zoomFrame->get_SummaryZoomCollection();
collection->RemoveSummaryZoomSection(pres->get_Sections()->idx_get(1));
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISection](../../isection/)
* Osztály [SummaryZoomSectionCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)