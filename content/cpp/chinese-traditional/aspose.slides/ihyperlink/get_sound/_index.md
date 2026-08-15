---
title: get_Sound()
second_title: Aspose.Slides for C++ API 參考
description: 表示超連結的播放聲音。請閱讀 IAudio.
type: docs
weight: 183
url: /zh-hant/aspose.slides/ihyperlink/get_sound/
---
## IHyperlink::get_Sound() 方法


表示超連結的播放聲音。請閱讀 [IAudio](../../iaudio/).

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IHyperlink::get_Sound()=0
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




## 另見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IAudio](../../iaudio/)
* 類別 [IHyperlink](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)