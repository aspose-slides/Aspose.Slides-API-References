---
title: GetFontName()
second_title: Aspose.Slides for C++ API Reference
description: Returns the font name, replacing theme referrence with an actual font used.
type: docs
weight: 27
url: /aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) method


Returns the font name, replacing theme referrence with an actual font used.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) from which themed font name should be taken. Its up to caller to provide a correct value. See [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### Return Value

Font name.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* Class [FontData](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)