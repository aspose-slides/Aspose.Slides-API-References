---
title: Presentation()
second_title: Aspose.Slides for C++ API 參考
description: 此建構函式從頭建立新的簡報。建立的簡報包含一張空白投影片。
type: docs
weight: 417
url: /zh-hant/aspose.slides/presentation/presentation/
---
## Presentation::Presentation() 建構函式

此建構函式從頭建立新的簡報。建立的簡報包含一張空投影片。

```cpp
Aspose::Slides::Presentation::Presentation()
```

## Presentation::Presentation(System::SharedPtr\<Aspose::Slides::LoadOptions\>) 建構函式

此建構函式從頭建立新的簡報。建立的簡報包含一張空投影片。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 其他載入選項。 |

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>) 建構函式

此建構函式是讀取現有 [Presentation](../) 的主要機制。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸入串流。 |

## 備註

```cpp
auto fis = MakeObject<IO::FileStream>(u"demo.pptx", IO::FileMode::Open, IO::FileAccess::Read);
auto pres = MakeObject<Presentation>(fis);
fis->Close();
```

## Presentation::Presentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::LoadOptions\>) 建構函式

此建構函式是讀取現有 [Presentation](../) 的主要機制。

```cpp
Aspose::Slides::Presentation::Presentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 輸入串流。 |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 其他載入選項。 |

## Presentation::Presentation(System::String) 建構函式

此建構函式取得來源檔案路徑，並從中讀取 [Presentation](../) 的內容。

```cpp
Aspose::Slides::Presentation::Presentation(System::String file)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 輸入檔案。 |

## 備註

```cpp
auto pres = MakeObject<Presentation>(u"demo.pptx");
```

## Presentation::Presentation(System::String, System::SharedPtr\<Aspose::Slides::LoadOptions\>) 建構函式

此建構函式取得來源檔案路徑，並從中讀取 [Presentation](../) 的內容。

```cpp
Aspose::Slides::Presentation::Presentation(System::String file, System::SharedPtr<Aspose::Slides::LoadOptions> loadOptions)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | 輸入檔案。 |
| loadOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../../loadoptions/)\> | 其他載入選項。 |

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [Presentation](../)
* 類別 [LoadOptions](../../loadoptions/)
* 類別 [Stream](../../../system.io/stream/)
* 類別 [String](../../../system/string/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)