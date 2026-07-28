---
title: RemoveSummaryZoomSection()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja a Summary Zoom Section objektumot a gyűjteményből.
type: docs
weight: 40
url: /hu/aspose.slides/isummaryzoomsectioncollection/removesummaryzoomsection/
---
## ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr\<ISection\>) metódus

Eltávolítja a Summary Zoom [Section](../../section/) objektumot a gyűjteményből.

```cpp
virtual void Aspose::Slides::ISummaryZoomSectionCollection::RemoveSummaryZoomSection(System::SharedPtr<ISection> section)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) amelyhez a Summary Zoom [Section](../../section/) elemet el kell távolítani [ISection](../../isection/). |
## Megjegyzések

A példa bemutatja a Summary Zoom [Section](../../section/) elem index szerinti lekérését: 
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
* Osztály [ISummaryZoomSectionCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)