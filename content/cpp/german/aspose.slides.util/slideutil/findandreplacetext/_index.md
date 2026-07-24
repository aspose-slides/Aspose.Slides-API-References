---
title: FindAndReplaceText()
second_title: Aspose.Slides für C++ API Referenz
description: Findet und ersetzt Text in der Präsentation mit dem angegebenen Format
type: docs
weight: 40
url: /de/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method


Findet und ersetzt Text in der Präsentation mit dem angegebenen Format

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Durchsuchte Präsentation. |
| withMasters | **bool** | Bestimmt, ob Masterfolien durchsucht werden sollen. |
| find | [System::String](../../../system/string/) | Zu findender Zeichenfolgenwert. |
| replace | [System::String](../../../system/string/) | Zu ersetzender Zeichenfolgenwert. |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | Format für das Ersetzen des Textabschnitts. Wenn null, wird das Format des ersten Zeichens der gefundenen Zeichenfolge verwendet. |
## Bemerkungen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```




## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [PortionFormat](../../../aspose.slides/portionformat/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)