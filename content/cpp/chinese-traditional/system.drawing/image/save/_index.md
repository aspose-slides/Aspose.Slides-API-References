---
title: Save()
second_title: Aspose.Slides for C++ API 參考
description: 將目前物件所表示的影像以 PNG 格式儲存至指定檔案。
type: docs
weight: 1
url: /zh-hant/system.drawing/image/save/
---
## Image::Save(const String\&) 方法


將目前物件所表示的影像以 PNG 格式儲存至指定檔案。

```cpp
void System::Drawing::Image::Save(const String &filename)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 儲存影像的檔案名稱 |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) 方法


將目前物件所表示的影像以指定的格式儲存至指定檔案。

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 儲存影像的檔案名稱 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 用來儲存影像的格式 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) 方法


將目前物件所表示的影像以指定的格式儲存至指定的串流。

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 用來儲存影像的串流 |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | 用來儲存影像的格式 |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) 方法


將目前物件所表示的影像使用指定的編碼器與編碼參數儲存至指定檔案。

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | 儲存影像的檔案名稱 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 要使用的編碼器 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的編碼器參數 |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) 方法


將目前物件所表示的影像使用指定的編碼器與編碼參數儲存至指定的串流。

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | 用來儲存影像的串流 |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | 要使用的編碼器 |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | 要使用的編碼器參數 |

## 另請參閱

* 型別別名 [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* 型別別名 [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* 類別 [String](../../../system/string/)
* 類別 [Image](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)