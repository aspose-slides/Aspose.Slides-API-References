---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的路徑和建立模式建立 FileStream。
type: docs
weight: 14
url: /zh-hant/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) 方法

使用指定的路徑和建立模式建立 FileStream。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | 檔案名稱 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | 檔案模式 [System::IO::FileMode](../../../system.io/filemode/) |

### 回傳值

COM 介面的串流封裝 [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) 方法

使用指定的路徑、建立模式和讀寫權限建立 FileStream。

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | 檔案名稱 [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | 檔案模式 [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | 檔案存取 [System::IO::FileAccess](../../../system.io/fileaccess/) |

### 回傳值

COM 介面的串流封裝 [IStreamWrapper](../../istreamwrapper/)

## 另請參閱

* 列舉 [FileMode](../../../system.io/filemode/)
* 列舉 [FileAccess](../../../system.io/fileaccess/)
* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IStreamWrapper](../../istreamwrapper/)
* 類別 [String](../../../system/string/)
* 類別 [IStreamWrapperFactory](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)