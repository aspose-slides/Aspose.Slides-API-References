---
title: Bitmap()
second_title: Aspose.Slides for C++ API 參考
description: 從指定的現有圖像建構一個新的 Bitmap 物件。
type: docs
weight: 1
url: /zh-hant/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) 建構函式

從指定的現有圖像建構一個新的 [Bitmap](../) 物件。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於建立位圖影像的現有圖像 |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) 建構函式

從指定的串流建構一個新的 [Bitmap](../) 物件。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 包含圖像資料的串流 |
| useIcm | **bool** | 已忽略 |

## Bitmap::Bitmap(const String\&) 建構函式

從指定的檔案建構一個新的 [Bitmap](../) 物件。

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 包含圖像資料的檔案名稱 |

## Bitmap::Bitmap(const String\&, bool) 建構函式

從指定的檔案建構一個新的 [Bitmap](../) 物件。

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 包含圖像資料的檔案名稱 |
| useIcm | **bool** | 已忽略 |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) 建構函式

建構一個新的 [Bitmap](../) 物件，該物件表示具有指定寬度、高度、像素格式和像素資料的位圖影像。

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| width | int | 圖像的寬度 |
| height | int | 圖像的高度 |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | 圖像的像素格式 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) 建構函式

從指定的現有圖像建構一個新的 [Bitmap](../) 物件，並依指定的尺寸縮放。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於建立位圖影像的現有圖像 |
| size | const [Size](../../size/)\& | 新圖像的尺寸 |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) 建構函式

從指定的現有圖像建構一個新的 [Bitmap](../) 物件，並將寬度與高度縮放至指定的數值。

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | 用於建立位圖影像的現有圖像 |
| width | int | 新圖像的寬度 |
| height | int | 新圖像的高度 |

## 另見

* 列舉 [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Image](../../image/)
* 類別 [Bitmap](../)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [String](../../../system/string/)
* 類別 [Size](../../size/)
* 命名空間 [System::Drawing](../../)
* 程式庫 [Aspose.Slides](../../../)