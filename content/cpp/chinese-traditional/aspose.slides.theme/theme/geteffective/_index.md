---
title: GetEffective()
second_title: Aspose.Slides for C++ API 參考
description: 取得套用繼承後的有效佈景主題資料。
type: docs
weight: 53
url: /zh-hant/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() 方法

取得套用繼承後的有效佈景主題資料。

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```

### 返回值

一個 [IThemeEffectiveData](../../ithemeeffectivedata/)。

## 備註

此範例示範如何取得有效的佈景主題屬性。 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IThemeEffectiveData](../../ithemeeffectivedata/)
* 類別 [Theme](../)
* 命名空間 [Aspose::Slides::Theme](../../)
* 函式庫 [Aspose.Slides](../../../)