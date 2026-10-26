---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効なテーマデータを取得します。
type: docs
weight: 53
url: /ja/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() メソッド

継承が適用された有効なテーマデータを取得します。

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### 戻り値

[IThemeEffectiveData](../../ithemeeffectivedata/)。

## 備考

この例は、有効なテーマプロパティの取得方法を示しています。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IThemeEffectiveData](../../ithemeeffectivedata/)
* クラス [Theme](../)
* 名前空間 [Aspose::Slides::Theme](../../)
* ライブラリ [Aspose.Slides](../../../)