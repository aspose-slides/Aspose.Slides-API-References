---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得簡報渲染時將被取代的字型資訊。
type: docs
weight: 66
url: /zh-hant/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() method


取得簡報渲染時將被取代的字型資訊。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### 返回值

所有字型取代的集合 [FontSubstitutionInfo](../../fontsubstitutioninfo/)。
## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) method


取得指定投影片渲染時將被取代的字型資訊。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 一個陣列，包含要取得字型取代資訊的投影片索引，索引從 1 開始。 |

### 返回值

指定投影片的所有字型取代集合 ([FontSubstitutionInfo](../../fontsubstitutioninfo/))。

## 備註




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* 類別 [IFontsManager](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)