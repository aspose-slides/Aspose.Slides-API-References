---
title: LoadingStreamBehavior
second_title: Aspose.Slides for C++ API 參考文件
description: "傳遞給方法的 System::IO::Stream 被視為二進位大型物件 (BLOB)（請參閱 IBlobManagementOptions 說明）。此列舉的值說明在將 System::IO::Stream 傳遞給方法時應如何處理它。根據需求，可做出不同決策以提供最高效的行為。"
type: docs
weight: 6735
url: /zh-hant/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 列舉

[System::IO::Stream](../../system.io/stream/) 傳遞給方法時被視為二進位大型物件 (BLOB)（請參閱 [IBlobManagementOptions](../iblobmanagementoptions/) 說明）。此列舉的值說明在將 [System::IO::Stream](../../system.io/stream/) 傳遞給方法時應如何處理它。根據需求，可做出不同決策以提供最高效的行為。

```cpp
enum class LoadingStreamBehavior
```

### Values

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | 串流將被讀取至結尾後釋放——亦即保證未來 [IPresentation](../ipresentation/) 實例不會再使用此串流。它可以由客戶端程式碼關閉，或以其他任何方式使用。 |
| KeepLocked | 1 | 串流將被鎖定於 [IPresentation](../ipresentation/) 物件內，即串流的所有權會被轉移。[IPresentation](../ipresentation/) 物件負責在此物件本身被釋放時正確處理串流的釋放。當您需要序列化大型 BLOB 檔案（例如大型影片或音訊——請參閱 [IBlobManagementOptions](../iblobmanagementoptions/) 說明）且想避免將此檔案載入記憶體或其他效能問題時，此行為極為有用。您只需為該檔案開啟 [System::IO::FileStream](../../system.io/filestream/)，並傳遞給方法，同時選擇 [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior。 |

## 參見

* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)