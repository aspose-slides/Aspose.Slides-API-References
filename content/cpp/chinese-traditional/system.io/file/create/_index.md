---
title: Create()
second_title: Aspose.Slides for C++ API 參考文件
description: 建立新檔案（或覆寫現有檔案），並使用指定的緩衝區大小與選項開啟以供讀寫存取。
type: docs
weight: 53
url: /zh-hant/system.io/file/create/
---
## File::Create(const String&, int32_t, FileOptions) 方法

建立新檔案（或覆寫現有檔案），並使用指定的緩衝區大小與選項開啟以供讀寫。

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)& | 要建立或覆寫的檔案路徑 |
| bufferSize | **int32_t** | 從檔案讀取和寫入時緩衝的位元組數 |
| options | [FileOptions](../../fileoptions/) | 指定如何建立或覆寫檔案 |

### 返回值

與指定檔案相關聯的 [FileStream](../../filestream/) 物件的 shared pointer

## 另請參閱

* 列舉 [FileOptions](../../fileoptions/)
* 類型定義 [FileStreamPtr](../../../system/filestreamptr/)
* 類別 [String](../../../system/string/)
* 類別 [File](../)
* 命名空間 [System::IO](../../)
* 函式庫 [Aspose.Slides](../../../)