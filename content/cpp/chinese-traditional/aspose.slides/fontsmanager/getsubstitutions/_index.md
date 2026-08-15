---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API 參考
description: 取得有關在簡報渲染時將被取代的字體資訊。
type: docs
weight: 66
url: /zh-hant/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() 方法


取得有關在簡報渲染時將被替換的字體資訊。

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### 返回值

所有字體替換的集合 [FontSubstitutionInfo](../../fontsubstitutioninfo/)。
## 備註




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) 方法


取得有關在指定投影片渲染期間將被替換的字體資訊。

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 用於取得字體替換資訊的投影片索引陣列，索引從 1 起算。 |

### 返回值

針對指定投影片的所有字體替換集合 ([FontSubstitutionInfo](../../fontsubstitutioninfo/))。

## 備註




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)