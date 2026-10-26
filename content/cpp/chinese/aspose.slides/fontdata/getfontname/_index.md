---
title: GetFontName()
second_title: Aspose.Slides C++ API 参考
description: 返回字体名称，将主题引用替换为实际使用的字体。
type: docs
weight: 27
url: /zh/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) 方法

返回字体名称，将主题引用替换为实际使用的字体。

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) 从中获取主题字体名称。调用者需提供正确的值。参见 [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### 返回值

字体名称。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* 类 [FontData](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)