---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API 参考
description: 在演示文稿中查找并替换文本，使用给定的格式
type: docs
weight: 40
url: /zh/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) method


在演示文稿中查找并替换文本，使用给定的格式

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 已扫描的演示文稿。 |
| withMasters | **bool** | 确定是否应扫描母版幻灯片。 |
| find | [System::String](../../../system/string/) | 要查找的字符串值。 |
| replace | [System::String](../../../system/string/) | 要替换的字符串值。 |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | 用于替换文本段的格式。如果为 null，则使用找到的字符串的第一个字符的格式 |
## 备注




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




## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [PortionFormat](../../../aspose.slides/portionformat/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)