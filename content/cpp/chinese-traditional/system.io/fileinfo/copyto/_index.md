---
title: CopyTo()
second_title: Aspose.Slides for C++ API 參考文件
description: 將目前物件所代表的檔案複製到指定位置。如果目的檔案已存在，則複製失敗。
type: docs
weight: 105
url: /zh-hant/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) 方法

將目前物件所代表的檔案複製到指定位置。如果目的檔案已存在，則複製失敗。

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | 目標檔案名稱 |

### 返回值

一個代表此複製的 [FileInfo](../) 物件

## FileInfo::CopyTo(const String\&, bool) 方法

將目前物件所代表的檔案複製到指定位置。此參數指定是否應覆寫已存在的目的檔案。

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | 目標檔案名稱 |
| overwrite | **bool** | 若應覆寫已存在的目的檔案則為 true，若目的檔案已存在則為 false，複製將失敗 |

### 返回值

一個代表此複製的 [FileInfo](../) 物件

## 另請參閱

* 類型別名 [FileInfoPtr](../../../system/fileinfoptr/)
* 類別 [String](../../../system/string/)
* 類別 [FileInfo](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)