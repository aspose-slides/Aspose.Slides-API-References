---
title: get_Sound()
second_title: Aspose.Slides for C++ API 参考
description: 表示超链接的播放声音。阅读 IAudio.
type: docs
weight: 183
url: /zh/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() 方法

表示超链接的播放声音。阅读 [IAudio](../../iaudio/)。

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
```

## 备注

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一个形状的超链接
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 提取超链接声音的字节数组
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IAudio](../../iaudio/)
* 类 [IHyperlink](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)