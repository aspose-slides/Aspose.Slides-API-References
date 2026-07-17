---
title: Slide()
second_title: Aspose.Slides for C++ API 参考
description: "遍历演示文稿中的每个 ForEach::Slide。"
type: docs
weight: 1
url: /zh/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) 方法

遍历每个 [ForEach::Slide](./) 在 [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历幻灯片 |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | 将在每个幻灯片上调用的回调 |
## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ForEachSlideCallback](../foreachslidecallback/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ForEach](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)