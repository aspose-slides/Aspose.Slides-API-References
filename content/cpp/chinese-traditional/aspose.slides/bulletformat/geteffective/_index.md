---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得套用繼承後的有效項目格式資料。
type: docs
weight: 248
url: /zh-hant/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() 方法


取得套用繼承後的有效項目格式資料。

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### 傳回值

一個 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)。
## 備註



此範例示範取得某些有效的項目格式屬性。
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* 類別 [BulletFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)