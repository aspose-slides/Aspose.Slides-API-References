---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 列舉

表示在載入和使用 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例時，對 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 來源（檔案或 **io.RawIOBase**）的處理行為。

PresentationLockingBehavior 類型公開以下成員：

## 欄位

| 欄位 | 說明 |
| :- | :- |
| LOAD_AND_RELEASE | 來源僅在 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 建構函式執行期間被鎖定。<br/>            如果 [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) 設為 false，所有 BLOB 會<br/>            載入記憶體。否則，可能會使用其他方式，例如暫存檔。本行為較 [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/zh-hant/aspose.slides/presentationlockingbehavior/KEEP_LOCKED) 慢，若可以將來源的所有權傳遞給 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)，建議使用 [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/zh-hant/aspose.slides/presentationlockingbehavior/KEEP_LOCKED)。 |
| KEEP_LOCKED | 來源在 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例的整個生命週期內被鎖定，直至其被釋放。<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/zh-hant/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) 必須設定為 true 才能使用<br/>            此行為，否則會拋出例外。此行為受到推薦，因為它比 [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/zh-hant/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE) 更快且佔用較少記憶體。 |

### 備註

來源是傳遞給 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 建構函式的參數。在下列範例中，來源是「pres.pptx」檔案：

對於此範例，來源（「pres.pptx」檔案）將在 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation) 實例的生命週期內被鎖定，也就是說其他程序無法變更或刪除它。

### 另請參閱
* 類別 [`IPresentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)