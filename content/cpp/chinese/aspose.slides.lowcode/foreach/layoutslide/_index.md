---
title: LayoutSlide()
second_title: Aspose.Slides for C++ API 参考
description: "遍历演示文稿中的每个 ForEach::LayoutSlide。"
type: docs
weight: 27
url: /zh/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) 方法


遍历 [Presentation](../../../aspose.slides/presentation/) 中的每个 [ForEach::LayoutSlide](./).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历布局幻灯片 |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | 将在每个布局幻灯片上调用的回调 |
## 备注




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ForEach](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)