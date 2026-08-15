---
title: Add()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 WebVTT 隱蔽字幕加入集合的尾端。
type: docs
weight: 27
url: /zh-hant/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) 方法

將 WebVTT 隱蔽字幕加入集合的尾端。

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 隱蔽字幕的標籤。 |
| filePath | [System::String](../../../system/string/) | WebVTT 檔案的路徑。 |

### 回傳值

已新增的 [ICaptions](../../icaptions/) 實例。

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) 方法

將 WebVTT 隱蔽字幕從串流加入集合的尾端。

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 隱蔽字幕的標籤。 |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含 WebVTT 格式資料的輸入串流。 |

### 回傳值

已新增的 [ICaptions](../../icaptions/) 實例。

## 參見

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICaptions](../../icaptions/)
* 類別 [String](../../../system/string/)
* 類別 [ICaptionsCollection](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides](../../)
* 庫 [Aspose.Slides](../../../)