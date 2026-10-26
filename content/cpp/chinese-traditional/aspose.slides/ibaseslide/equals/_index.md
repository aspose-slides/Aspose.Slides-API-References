---
title: Equals()
second_title: Aspose.Slides for C++ API 參考
description: 判斷兩個 IBaseSlide 實例是否相等。回傳值根據投影片的結構和靜態內容計算。如果所有形狀、樣式、文字、動畫以及其他設定等都相等，則兩張投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，及動態內容，例如 Date Placeholder 中的目前日期值。
type: docs
weight: 183
url: /zh-hant/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) 方法


判斷兩個 [IBaseSlide](../) 實例是否相等。回傳值根據投影片的結構和靜態內容計算。如果所有形狀、樣式、文字、動畫以及其他設定等都相等，則兩張投影片相等。比較不會考慮唯一識別碼值，例如 SlideId，及動態內容，例如 Date [Placeholder](../../placeholder/) 中的目前日期值。

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | 用於與目前的 [IBaseSlide](../) 比較的 [IBaseSlide](../)。 |

### 回傳值

**true** 如果指定的 [IBaseSlide](../) 等於目前的 [IBaseSlide](../)；否則為 **false**。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IBaseSlide](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)