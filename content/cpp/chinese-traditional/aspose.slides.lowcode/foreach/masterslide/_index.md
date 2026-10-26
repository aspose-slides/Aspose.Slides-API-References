---
title: MasterSlide()
second_title: Aspose.Slides for C++ API 參考
description: "遍歷 Presentation 中的每個 ForEach::MasterSlide。"
type: docs
weight: 14
url: /zh-hant/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::MasterSlide](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於遍歷母片幻燈片 |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | 回呼函式，將於每個母片幻燈片被呼叫 |

## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [ForEach](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 函式庫 [Aspose.Slides](../../../)