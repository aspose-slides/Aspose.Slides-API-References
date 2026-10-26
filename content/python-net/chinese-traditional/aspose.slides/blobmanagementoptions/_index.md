---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions 類別

代表可用於管理 BLOB 處理規則和其他 BLOB 設定的選項。

BlobManagementOptions 類型公開以下成員：

## 建構式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions/__init__/#) | 建立新的預設 BLOB 管理選項。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | 此屬性定義 Presentation 類別的實例在其生命週期內是否可以成為來源 - 檔案<br/>            或串流的擁有者。若實例為擁有者，則會鎖定來源。這有助於<br/>            改善記憶體使用量和效能，同時處理 BLOB 時，但在 Presentation 實例的生命週期內<br/>            無法變更來源（串流或檔案）。 |
| [`is_temporary_files_allowed`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | 此屬性定義在處理 BLOB 時是否可以建立暫存檔，這大幅<br/>            降低記憶體使用量，但需要建立檔案的權限。<br/>            所有檔案會在簡報工作完成後被刪除。 |
| [`temp_files_root_path`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions/temp_files_root_path/) | 建立暫存檔的根目錄路徑。預設使用系統暫存目錄。<br/>            主機程序應具備在該處<br/>            建立檔案和資料夾的權限。 |
| [`max_blobs_bytes_in_memory`](/slides/python-net/zh-hant/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | 定義所有 BLOB 在記憶體中可能佔用的最大總大小（以位元組為單位）。預設情況下，所有 BLOB<br/>            皆載入記憶體；只有在達到此限制時才會使用替代機制（如暫存檔）。將 BLOB 保留在記憶體中可最大化效能，但可能導致高記憶體使用量。使用此屬性可依據您的環境或需求調整行為。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)