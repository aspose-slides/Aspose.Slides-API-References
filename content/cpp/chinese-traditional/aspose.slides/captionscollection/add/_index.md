---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 將 WebVTT 隱藏式字幕新增至集合的末端。
type: docs
weight: 27
url: /zh-hant/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) 方法

將 WebVTT 隱藏式字幕新增至集合的末端。

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 隱藏式字幕的標籤。 |
| filePath | [System::String](../../../system/string/) | WebVTT 檔案的路徑。 |

### 傳回值

已新增的 [ICaptions](../../icaptions/) 實例。

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) 方法

從資料流將 WebVTT 隱藏式字幕新增至集合的末端。

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | 隱藏式字幕的標籤。 |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含 WebVTT 格式資料的輸入串流。 |

### 傳回值

已新增的 [ICaptions](../../icaptions/) 實例。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ICaptions](../../icaptions/)
* 類別 [String](../../../system/string/)
* 類別 [CaptionsCollection](../)
* 類別 [Stream](../../../system.io/stream/)
* 名稱空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)