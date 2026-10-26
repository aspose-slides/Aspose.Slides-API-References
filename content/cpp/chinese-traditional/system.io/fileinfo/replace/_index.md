---
title: Replace()
second_title: Aspose.Slides for C++ API 參考
description: 將指定目標檔案的內容以目前 FileInfo 物件所代表的檔案取代，並為被取代的檔案建立備份。
type: docs
weight: 131
url: /zh-hant/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) 方法

將指定目標檔案的內容以目前 [FileInfo](../) 物件所代表的檔案取代，並為被取代的檔案建立備份。

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 要取代的檔案名稱 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 備份檔案的名稱 |

### 傳回值

一個 FileInfor 物件，代表由 **destinationFileName** 指向的檔案

## FileInfo::Replace(const String\&, const String\&, bool) 方法

將指定目標檔案的內容以目前 [FileInfo](../) 物件所代表的檔案取代，並為被取代的檔案建立備份。

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 要取代的檔案名稱 |
| destinationBackupFileName | const [String](../../../system/string/)\& | 備份檔案的名稱 |
| ignoreMetadataErrors | **bool** | 指定是否應忽略從被取代檔案合併到取代檔案的錯誤 (true) 或不忽略 (false) |

### 傳回值

一個 FileInfor 物件，代表由 **destinationFileName** 指向的檔案

## 另請參閱

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* 類別 [String](../../../system/string/)
* 類別 [FileInfo](../)
* 命名空間 [System::IO](../../)
* 程式庫 [Aspose.Slides](../../../)