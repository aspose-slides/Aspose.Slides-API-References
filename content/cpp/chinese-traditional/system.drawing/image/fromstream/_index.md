---
title: FromStream()
second_title: Aspose.Slides for C++ API 參考
description: 從指定的串流建立 Image 物件。
type: docs
weight: 339
url: /zh-hant/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) 方法

從指定的串流建立 [Image](../) 物件。

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 包含影像資料的串流 |
| use_embedded_color_management | **bool** | 已忽略 |
| validate_image_data | **bool** | 已忽略 |

### 回傳值

指向已建立的 [Image](../) 物件的 shared pointer。

## 參見

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Image](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)