---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API 參考
description: 從陣列讀取現有簡報
type: docs
weight: 27
url: /zh-hant/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) 方法

從陣列讀取現有簡報

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要讀取的陣列 |

### 回傳值

讀取的簡報

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) 方法

從陣列讀取現有簡報，並使用額外的載入選項

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要讀取的陣列 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 回傳值

讀取的簡報

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) 方法

從串流讀取現有簡報

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要讀取的輸入串流 |

### 回傳值

讀取的簡報

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) 方法

從串流讀取現有簡報，並使用額外的載入選項

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要讀取的輸入串流 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 回傳值

讀取的簡報

## IPresentationFactory::ReadPresentation(System::String) 方法

從檔案讀取現有簡報

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 檔案名稱 |

### 回傳值

讀取的簡報

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) 方法

從檔案讀取現有簡報，並使用額外的載入選項

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 檔案名稱 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 回傳值

讀取的簡報

## 參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IPresentation](../../ipresentation/)
* Class [IPresentationFactory](../)
* Class [ILoadOptions](../../iloadoptions/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)