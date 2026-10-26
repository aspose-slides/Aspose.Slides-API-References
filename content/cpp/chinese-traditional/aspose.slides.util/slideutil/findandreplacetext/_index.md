---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API 參考
description: 在簡報中尋找並取代文字，並使用指定格式
type: docs
weight: 40
url: /zh-hant/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method

在簡報中尋找並取代文字，並套用指定格式

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 已掃描的簡報。 |
| withMasters | **bool** | 決定是否應掃描母片投影片。 |
| find | [System::String](../../../system/string/) | 要尋找的字串值。 |
| replace | [System::String](../../../system/string/) | 要取代的字串值。 |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | 取代文字段落的格式。如果為 null，則使用找到字串的第一個字元的格式 |

## 備註




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



## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPresentation](../../../aspose.slides/ipresentation/)
* 類別 [String](../../../system/string/)
* 類別 [PortionFormat](../../../aspose.slides/portionformat/)
* 類別 [SlideUtil](../)
* 命名空間 [Aspose::Slides::Util](../../)
* 程式庫 [Aspose.Slides](../../../)