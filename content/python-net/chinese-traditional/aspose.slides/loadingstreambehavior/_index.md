---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior 列舉

傳遞給方法的 **io.RawIOBase** 被視為二進位大型物件 (BLOB)（請參閱 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions) 說明）。此列舉的值用於標示在傳遞給方法時 **io.RawIOBase** 應該如何處理。根據需求，可做出不同的決策以提供最有效的行為。

LoadingStreamBehavior 類型公開以下成員：

## 欄位

| Field | 說明 |
| :- | :- |
| READ_STREAM_AND_RELEASE | 此串流會讀取至結束，然後釋放——即保證未來 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例不會再使用此串流。<br/>            它可以由客戶端程式碼關閉，或以任何其他方式使用。 |
| KEEP_LOCKED | 此串流會被鎖定於 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 物件內，即串流的所有權將被轉移。<br/>            [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 物件將負責在此物件本身被處置時正確釋放串流。<br/>            此行為在需要序列化大型 BLOB 檔案（例如大型影片或音訊 -請參閱 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions) 說明）且想避免將該檔案載入記憶體或其他效能問題時極為有用。您只需為此檔案開啟 **System.IO.FileStream** <br/>            並傳遞給方法，選擇 [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior。 |

### 另請參閱
* 類別 [`IBlobManagementOptions`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions)
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)