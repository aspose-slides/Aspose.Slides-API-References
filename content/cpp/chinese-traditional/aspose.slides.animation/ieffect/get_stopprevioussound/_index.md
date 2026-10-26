---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API 參考文件
description: 此屬性指定動畫效果是否停止先前的聲音。讀取 bool.
type: docs
weight: 196
url: /zh-hant/aspose.slides.animation/ieffect/get_stopprevioussound/
---
## IEffect::get_StopPreviousSound() 方法

此屬性指定動畫效果是否停止先前的聲音。讀取 **bool**.

```cpp
virtual bool Aspose::Slides::Animation::IEffect::get_StopPreviousSound()=0
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
    // 將第二個效果的增強/聲音改為「停止先前的聲音」
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## 另請參閱

* 類別 [IEffect](../)
* 命名空間 [Aspose::Slides::Animation](../../)
* 函式庫 [Aspose.Slides](../../../)