---
title: Equals()
second_title: Aspose.Slides for C++ API 參考
description: 判斷兩個 IBaseSlide 實例是否相等。返回值根據投影片的結構和靜態內容計算。若所有形狀、樣式、文字、動畫以及其他設定等全部相同，則兩個投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，以及動態內容，例如 Date Placeholder 中的當前日期值。
type: docs
weight: 170
url: /zh-hant/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) 方法

判斷兩個 [IBaseSlide](../../ibaseslide/) 實例是否相等。返回值根據投影片的結構和靜態內容計算。若所有形狀、樣式、文字、動畫以及其他設定等全部相同，則兩個投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，以及動態內容，例如 Date [Placeholder](../../placeholder/) 中的當前日期值。

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### 參數

| 參數 | 類型 |說明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | 與目前的 [IBaseSlide](../../ibaseslide/) 比較的 [IBaseSlide](../../ibaseslide/)。 |

### 返回值

**true** 如果指定的 [IBaseSlide](../../ibaseslide/) 與目前的 [IBaseSlide](../../ibaseslide/) 相等；否則 **false**。

## 備註

以下範例說明如何比較兩個投影片。 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBaseSlide](../../ibaseslide/)
* Class [BaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)