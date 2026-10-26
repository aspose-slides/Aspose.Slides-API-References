---
title: GetFontName()
second_title: Aspose.Slides for C++ API 參考
description: 返回字體名稱，將主題參考取代為實際使用的字體。
type: docs
weight: 27
url: /zh-hant/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) 方法


返回字體名稱，將主題參考取代為實際使用的字體。

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) 從中取得主題字體名稱。由呼叫端提供正確的值。請參閱 [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### 返回值

字體名稱。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* 類別 [FontData](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)