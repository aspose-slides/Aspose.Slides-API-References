---
title: GetEffective()
second_title: Aspose.Slides for C++ API 参考
description: 获取已应用继承的有效主题数据。
type: docs
weight: 53
url: /zh/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() 方法


获取已应用继承的有效主题数据。

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### 返回值

一个 [IThemeEffectiveData](../../ithemeeffectivedata/).
## 备注



此示例演示了获取有效主题属性。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IThemeEffectiveData](../../ithemeeffectivedata/)
* 类 [Theme](../)
* 命名空间 [Aspose::Slides::Theme](../../)
* Library [Aspose.Slides](../../../)