---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions 類別

Binary Large Object（BLOB）是一種以單一實體儲存的二進位資料——也就是說，BLOB 可以是音訊、影片或簡報本身。使用多種技術來最佳化處理 BLOB 時的記憶體消耗——無論是已儲存在簡報中，或稍後以程式方式加入。使用 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions) 您可以變更與 BLOB 處理相關的不同行為面向，以配合 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例的生命週期。

The IBlobManagementOptions type exposes the following members:

## 屬性

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | 此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源（檔案<br/>或串流）的擁有者。若實例是擁有者，則會鎖定來源。這有助於在處理 BLOB 時<br/>提升記憶體使用與性能，但在 Presentation 實例的生命週期內，來源（串流或檔案）<br/>無法被變更。以下為示例： |
| [`is_temporary_files_allowed`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | 此屬性定義在處理 BLOB 時是否可以建立暫存檔案，這可大幅降低記憶體使用，然而需要具備建立檔案的權限。<br/>所有檔案會在簡報工作完成後被刪除。 |
| [`temp_files_root_path`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | 暫存檔案將建立的根目錄。預設使用系統暫存目錄。<br/>主機程式應具備在該處<br/>建立檔案與資料夾的權限。 |
| [`max_blobs_bytes_in_memory`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | 定義所有 BLOB 在記憶體中可佔用的最大總大小（以位元組為單位）。預設情況下，會將所有 BLOB<br/>載入記憶體；僅當達到此上限時，才會採用其他機制（例如暫存檔）。將 BLOB 保留於記憶體可提升效能，但可能導致記憶體使用量偏高。請使用此屬性依據您的環境或需求調整行為。 |

### 另見
* 類別 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)