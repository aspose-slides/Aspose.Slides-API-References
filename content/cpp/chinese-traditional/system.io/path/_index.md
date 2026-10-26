---
title: Path
second_title: Aspose.Slides for C++ API 參考文件
description: 提供用於操作路徑的方法。這是一個靜態類型，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 339
url: /zh-hant/system.io/path/
---
## Path 類別

提供用於操作路徑的方法。這是一個靜態類型，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
class Path
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 變更指定檔案路徑的副檔名。 |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | 透過檢查指定路徑是否包含無效字元來判斷其是否有效。若路徑包含無效字元，將拋出例外。 |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | 將指定的路徑段合併成單一路徑，必要時在段之間插入目錄分隔字元。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將兩個指定的路徑段合併成單一路徑，必要時在段之間插入目錄分隔字元。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將三個指定的路徑段合併成單一路徑，必要時在段之間插入目錄分隔字元。 |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 將四個指定的路徑段合併成單一路徑，必要時在段之間插入目錄分隔字元。 |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | 傳回由指定路徑參照的目錄名稱。 |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | 傳回由指定路徑參照的檔案副檔名。 |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | 傳回由指定路徑參照的檔案名稱。 |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | 傳回由指定路徑參照的檔案不含副檔名的名稱。 |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | 將指定路徑轉換為絕對路徑。 |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | 傳回包含檔案名稱中不允許使用之字元的陣列。 |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | 傳回包含路徑名稱中不允許使用之字元的陣列。 |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | 傳回指定路徑的根目錄。 |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | 傳回隨機產生的檔案名稱。 |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | 建立具有唯一名稱的新檔案，並傳回其完整路徑。 |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | 建立具有唯一名稱的新檔案，並傳回其完整路徑。是 [GetTempFileName_()](./gettempfilename_/) 方法的同義詞。 |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | 傳回當前使用者的暫存目錄路徑。 |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | 判斷指定路徑是否參照具有副檔名的檔案。 |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | 判斷指定路徑是否包含根目錄。 |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | 正規化指定的路徑。 |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | 傳回表示指定路徑的 boost::filesystem::path 類別實例。 |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | 傳回指定 Boost 路徑物件的字串表示。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | 用於在路徑中分隔目錄層級的替代字元。 |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | 用於在路徑中分隔目錄層級的字元。 |
| static [PathSeparator](./pathseparator/) | 用於在環境變數中分隔路徑字串的分隔字元。 |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | 磁碟分割字元。 |

## 備註



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // 產生隨機檔案名稱。
  auto filename = Path::GetRandomFileName();

  // 列印檔案名稱的資訊。
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
此程式碼範例產生以下輸出：
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## 參見

* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)