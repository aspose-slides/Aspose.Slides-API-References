---
title: LockBits()
second_title: Aspose.Slides C++ 版 API 參考
description: 將 Bitmap 鎖定至系統記憶體。
type: docs
weight: 118
url: /zh-hant/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) 方法

將 [Bitmap](../) 鎖定至系統記憶體。

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 指定要鎖定的影像區域的矩形 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | 指定位圖的存取層級 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 此位圖的資料格式 |

### 傳回值

指向 BitmapData 物件的共享指標，該物件包含有關執行的鎖定操作的資訊

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) 方法

將 [Bitmap](../) 鎖定至系統記憶體。

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 指定要鎖定的影像區域的矩形 |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | 指定位圖的存取層級 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 此位圖的資料格式 |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | 包含有關鎖定操作的資訊 |

### 傳回值

指向 BitmapData 物件的共享指標，該物件包含有關執行的鎖定操作的資訊

## 另請參閱

* 列舉 [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* 列舉 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 型別別名 [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* 類別 [Rectangle](../../rectangle/)
* 類別 [Bitmap](../)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)