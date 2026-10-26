---
title: set_Sound()
second_title: Aspose.Slides C++ API 参考
description: 表示超链接的播放声音。写入 IAudio.
type: docs
weight: 300
url: /zh/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) 方法


表示超链接的播放声音。写入 [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## 备注



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 获取第一个形状的超链接
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 将超链接声音提取为字节数组
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IAudio](../../iaudio/)
* 类 [Hyperlink](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)