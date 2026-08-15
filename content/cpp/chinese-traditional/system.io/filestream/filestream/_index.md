---
title: FileStream()
second_title: Aspose.Slides for C++ API 參考
description: 建立 FileStream 類別的新實例，並使用指定的參數進行初始化。
type: docs
weight: 1
url: /zh-hant/system.io/filestream/filestream/
---
## FileStream::FileStream(const String&, FileMode) 建構函式


建立 [FileStream](../) 類別的新實例，並使用指定的參數進行初始化。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟之檔案的路徑。 |
| mode | [FileMode](../../filemode/) | 指定開啟檔案的模式。 |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, FileOptions) 建構函式


建立 [FileStream](../) 類別的新實例，並使用指定的參數進行初始化。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟之檔案的路徑。 |
| mode | [FileMode](../../filemode/) | 指定開啟檔案的模式。 |
| access | [FileAccess](../../fileaccess/) | 所請求的存取類型。 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../) 物件對已開啟檔案的存取類型。 |
| buffer_size | **int32_t** | 在讀寫操作期間緩衝的位元組數。 |
| options | [FileOptions](../../fileoptions/) | 其他選項。 |

## FileStream::FileStream(const String&, FileMode, FileAccess, FileShare, int32_t, bool) 建構函式


建立 [FileStream](../) 類別的新實例，並使用指定的參數進行初始化。

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 要開啟之檔案的路徑。 |
| mode | [FileMode](../../filemode/) | 指定開啟檔案的模式。 |
| access | [FileAccess](../../fileaccess/) | 所請求的存取類型。 |
| share | [FileShare](../../fileshare/) | 其他 [FileStream](../) 物件對已開啟檔案的存取類型。 |
| buffer_size | **int32_t** | 在讀寫操作期間緩衝的位元組數。 |
| useAsync | **bool** | 指定是使用非同步 I/O 還是同步 I/O。 |

## 備註



底層作業系統可能不支援非同步 I/O。 

## FileStream::FileStream(const FileStream&) 建構函式




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## 另請參閱

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)