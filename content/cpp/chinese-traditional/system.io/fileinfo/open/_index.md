---
title: Open()
second_title: Aspose.Slides for C++ API 參考
description: 以指定的模式開啟目前物件所代表的檔案，以讀寫且不共享。
type: docs
weight: 183
url: /zh-hant/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) 方法

以指定的模式開啟目前物件所代表的檔案，以讀寫並且不共享。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 指定開啟 flie 的模式 |

### 返回值

與此物件所代表的檔案相關聯的 [FileStream](../../filestream/) 物件

## FileInfo::Open(FileMode, FileAccess) 方法

以指定的模式及指定的存取類型開啟目前物件所代表的檔案，且不共享。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 指定開啟 flie 的模式 |
| access | [FileAccess](../../fileaccess/) | 請求的存取類型 |

### 返回值

與此物件所代表的檔案相關聯的 [FileStream](../../filestream/) 物件

## FileInfo::Open(FileMode, FileAccess, FileShare) 方法

以指定的模式、指定的存取類型與共享選項開啟目前物件所代表的檔案。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | 指定開啟 flie 的模式 |
| access | [FileAccess](../../fileaccess/) | 請求的存取類型 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../../filestream/) 物件對已開啟檔案的存取類型 |

### 返回值

與此物件所代表的檔案相關聯的 [FileStream](../../filestream/) 物件

## 另請參閱

* 列舉 [FileMode](../../filemode/)
* 列舉 [FileAccess](../../fileaccess/)
* 列舉 [FileShare](../../fileshare/)
* 型別別名 [FileStreamPtr](../../../system/filestreamptr/)
* 類別 [FileInfo](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)