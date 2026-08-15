---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API 參考
description: 從檔案建立新的 PresentationInfo 物件，並將簡報繫結至它。
type: docs
weight: 27
url: /zh-hant/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) 方法


從檔案建立新的 [PresentationInfo](../../presentationinfo/) 物件，並將簡報繫結至它。

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) 檔案。 |

### 傳回值

[Presentation](../../presentation/) 資訊已綁定至簡報。

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) 方法


從串流建立新的 [PresentationInfo](../../presentationinfo/) 物件，並將簡報繫結至它。取得指定串流中簡報的資訊。

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) 串流。 |

### 傳回值

[Presentation](../../presentation/) 資訊已綁定至簡報。

## 參見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IPresentationInfo](../../ipresentationinfo/)
* 類別 [String](../../../system/string/)
* 類別 [PresentationFactory](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)