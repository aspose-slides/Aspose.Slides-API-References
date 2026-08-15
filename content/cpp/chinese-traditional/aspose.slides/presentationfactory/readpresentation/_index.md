---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API 參考
description: 從陣列讀取現有的簡報
type: docs
weight: 40
url: /zh-hant/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) 方法

從陣列讀取現有的簡報

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要讀取的陣列 |

### 返回值

讀取簡報

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) 方法

從陣列讀取現有的簡報，並使用額外的載入選項

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要讀取的陣列 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 返回值

讀取簡報

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) 方法

從串流讀取現有的簡報

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要讀取的輸入串流 |

### 返回值

讀取簡報

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) 方法

從串流讀取現有的簡報，並使用額外的載入選項

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 要讀取的輸入串流 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 返回值

讀取簡報

## PresentationFactory::ReadPresentation(System::String) 方法

從檔案讀取現有的簡報

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 檔案名稱 |

### 返回值

讀取簡報

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) 方法

從檔案讀取現有的簡報，並使用額外的載入選項

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 檔案名稱 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | 載入選項 |

### 返回值

讀取簡報

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IPresentation](../../ipresentation/)
* 類別 [PresentationFactory](../)
* 類別 [ILoadOptions](../../iloadoptions/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [String](../../../system/string/)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)