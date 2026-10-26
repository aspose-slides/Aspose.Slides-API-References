---
title: Save()
second_title: Aspose.Slides for C++ API 參考文件
description: 將圖像儲存到檔案。
type: docs
weight: 40
url: /zh-hant/aspose.slides/iimage/save/
---
## IImage::Save(System::String) 方法

將圖像儲存到檔案。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 要儲存圖像的檔案路徑。 |

## IImage::Save(System::String, ImageFormat) 方法

將圖像以指定格式儲存到檔案。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 要儲存圖像的檔案路徑。 |
| format | [ImageFormat](../../imageformat/) | 圖像格式。 |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) 方法

將圖像以指定格式儲存到串流。

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要儲存圖像的串流。 |
| format | [ImageFormat](../../imageformat/) | 圖像格式。 |

## IImage::Save(System::String, ImageFormat, int32_t) 方法

將圖像以指定格式與品質儲存到檔案。

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | 要儲存圖像的檔案路徑。 |
| format | [ImageFormat](../../imageformat/) | 圖像格式。 |
| quality | **int32_t** | 儲存圖像的品質（0 到 100）。 

 此參數僅影響在 [ImageFormat::Jpeg](../../imageformat/) 中的儲存；對所有其他格式將被忽略。 |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) 方法

將圖像以指定格式與品質儲存到串流。

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要儲存圖像的串流。 |
| format | [ImageFormat](../../imageformat/) | 圖像格式。 |
| quality | **int32_t** | 儲存圖像的品質（0 到 100）。 

 此參數僅影響在 [ImageFormat::Jpeg](../../imageformat/) 中的儲存；對所有其他格式將被忽略。 |

## 參見

* Enum [ImageFormat](../../imageformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [IImage](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)