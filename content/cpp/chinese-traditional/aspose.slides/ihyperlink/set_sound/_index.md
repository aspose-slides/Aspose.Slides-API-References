---
title: set_Sound()
second_title: Aspose.Slides C++ API 參考文件
description: 表示超連結的播放聲音。寫入 IAudio.
type: docs
weight: 196
url: /zh-hant/aspose.slides/ihyperlink/set_sound/
---
## IHyperlink::set_Sound(System::SharedPtr\<IAudio\>) 方法

表示超連結的播放聲音。寫入[IAudio](../../iaudio/)。

```cpp
virtual void Aspose::Slides::IHyperlink::set_Sound(System::SharedPtr<IAudio> value)=0
```

## 備註

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一個形狀的超連結
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 提取超連結聲音的位元組陣列
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudio](../../iaudio/)
* 類別 [IHyperlink](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)