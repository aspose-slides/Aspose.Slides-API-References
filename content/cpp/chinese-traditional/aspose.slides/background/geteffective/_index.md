---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承後的有效背景資料。
type: docs
weight: 118
url: /zh-hant/aspose.slides/background/geteffective/
---
## Background::GetEffective() 方法

取得套用繼承後的有效背景資料。

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```

### 返回值

一個 [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)。

## 備註

此範例示範取得有效的背景屬性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* 類別 [Background](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)