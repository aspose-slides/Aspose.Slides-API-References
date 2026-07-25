---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効な段落書式データを取得します。
type: docs
weight: 365
url: /ja/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() メソッド


継承が適用された有効な段落書式データを取得します。

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### 戻り値

[IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/) を返します。
## 備考



この例では、いくつかの有効な段落書式プロパティの取得方法を示します。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* クラス [ParagraphFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)