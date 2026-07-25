---
title: GetEffective()
second_title: Aspose.Slides の C++ API リファレンス
description: 継承が適用された有効なテキストスタイルの書式設定データを取得します。
type: docs
weight: 27
url: /ja/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() method


継承が適用された有効なテキストスタイルの書式設定データを取得します。

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### 戻り値

A [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## 備考



この例は、有効なテキストスタイルプロパティの一部を取得する方法を示しています。 
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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* クラス [TextStyle](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)