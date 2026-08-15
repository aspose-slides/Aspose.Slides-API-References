---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承後的有效文字樣式格式資料。
type: docs
weight: 27
url: /zh-hant/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() 方法


取得套用繼承後的有效文字樣式格式資料。

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### 返回值

一個 [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## 備註



此範例示範取得部分有效文字樣式屬性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* 類別 [TextStyle](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)