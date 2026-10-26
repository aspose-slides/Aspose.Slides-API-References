---
title: set_Sound()
second_title: Aspose.Slides for C++ API 參考
description: 表示超連結的播放聲音。寫入 IAudio.
type: docs
weight: 300
url: /zh-hant/aspose.slides/hyperlink/set_sound/
---
## Hyperlink::set_Sound(System::SharedPtr\<IAudio\>) 方法


表示超連結的播放聲音。寫入 [IAudio](../../iaudio/).

```cpp
void Aspose::Slides::Hyperlink::set_Sound(System::SharedPtr<IAudio> value) override
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一個形狀的超連結
auto link = presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_HyperlinkClick();

if (link->get_Sound() != nullptr)
{
    // 以位元組陣列提取超連結聲音
    System::ArrayPtr<uint8_t> audioData = link->get_Sound()->get_BinaryData();
}
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudio](../../iaudio/)
* 類別 [Hyperlink](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)