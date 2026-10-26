---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API 參考文件
description: 此屬性指定動畫效果是否停止先前的聲音。寫入 bool。
type: docs
weight: 209
url: /zh-hant/aspose.slides.animation/effect/set_stopprevioussound/
---
## Effect::set_StopPreviousSound(bool) 方法


此屬性指定動畫效果是否停止先前的聲音。寫入 **bool**。

```cpp
void Aspose::Slides::Animation::Effect::set_StopPreviousSound(bool value) override
```

## 備註



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 取得第一張投影片的第一個效果。
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// 取得第二張投影片的第一個效果。
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // 將第二個效果的增強功能/聲音改為「Stop Previous Sound」
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 參見

* 類別 [Effect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 程式庫 [Aspose.Slides](../../../)