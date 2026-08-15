---
title: Slide()
second_title: Aspose.Slides for C++ API 參考文件
description: "遍歷 Presentation 中的每個 ForEach::Slide。"
type: docs
weight: 1
url: /zh-hant/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) 方法

遍歷 [Presentation](../../../aspose.slides/presentation/) 中的每個 [ForEach::Slide](./) 。

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用於遍歷投影片 |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | 將在每張投影片上被呼叫的回呼 |
## 備註

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類型別名 [ForEachSlideCallback](../foreachslidecallback/)
* 類別 [Presentation](../../../aspose.slides/presentation/)
* 類別 [ForEach](../)
* 命名空間 [Aspose::Slides::LowCode](../../)
* 程式庫 [Aspose.Slides](../../../)