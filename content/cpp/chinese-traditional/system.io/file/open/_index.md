---
title: Open()
second_title: Aspose.Slides for C++ API 參考
description: 以指定的模式開啟指定的檔案，供讀寫，且不共享。
type: docs
weight: 235
url: /zh-hant/system.io/file/open/
---
## File::Open(const String\&, FileMode) 方法

以指定的模式開啟指定的檔案，供讀寫，且不共享。

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟的檔案路徑 |
| mode | [FileMode](../../filemode/) | 指定開啟檔案的模式 |

### 返回值

與已開啟檔案關聯的 [FileStream](../../filestream/) 物件

## File::Open(const String\&, FileMode, FileAccess, FileShare) 方法

以指定的模式開啟指定的檔案，使用指定的存取類型和共享選項。

```cpp
static FileStreamPtr System::IO::File::Open(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::None)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟的檔案路徑 |
| mode | [FileMode](../../filemode/) | 指定開啟檔案的模式 |
| access | [FileAccess](../../fileaccess/) | 請求的存取類型 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../../filestream/) 物件對已開啟檔案的存取類型 |

### 返回值

與已開啟檔案關聯的 [FileStream](../../filestream/) 物件

## 另請參閱

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)