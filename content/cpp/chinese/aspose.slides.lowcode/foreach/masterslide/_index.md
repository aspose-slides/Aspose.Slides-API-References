---
title: MasterSlide()
second_title: Aspose.Slides C++ API 参考
description: "遍历演示文稿中的每个 ForEach::MasterSlide。"
type: docs
weight: 14
url: /zh/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) 方法

遍历 [Presentation](../../../aspose.slides/presentation/) 中的每个 [ForEach::MasterSlide](./)。

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 用于遍历主幻灯片 |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | 回调函数，将在每个主幻灯片上被调用 |

## 备注

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* 类 [Presentation](../../../aspose.slides/presentation/)
* 类 [ForEach](../)
* 命名空间 [Aspose::Slides::LowCode](../../)
* 库 [Aspose.Slides](../../../)