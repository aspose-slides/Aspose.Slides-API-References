---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides for C++ API 參考
description: 建立 MemoryStream 包裝器。
type: docs
weight: 1
url: /zh-hant/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() 方法


建立 MemoryStream 包裝器。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```


### 返回值

COM 介面的流包裝器 [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) 方法


根據指定的位元組陣列建立 MemoryStream 包裝器。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 位元組陣列 **uint8_t**[] |

### 返回值

COM 介面的流包裝器 [IStreamWrapper](../../istreamwrapper/)

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IStreamWrapper](../../istreamwrapper/)
* 類別 [IStreamWrapperFactory](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)