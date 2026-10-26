---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定檔案中的簡報資訊。
type: docs
weight: 14
url: /zh-hant/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) 方法

取得指定檔案中的簡報資訊。

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) 檔案。 |

### 返回值

[Presentation](../../presentation/) 資訊

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) 方法

取得指定串流中的簡報資訊。

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) 串流。 |

### 返回值

[Presentation](../../presentation/) 資訊。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IPresentationInfo](../../ipresentationinfo/)
* 類別 [String](../../../system/string/)
* 類別 [IPresentationFactory](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)