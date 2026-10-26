---
title: Details_FileNotFoundException
second_title: Aspose.Slides for C++ API 參考
description: "當嘗試存取磁碟上不存在的檔案時拋出的例外。切勿手動建立此類別的實例。請改用 FileNotFoundException 類別。切勿將 FileNotFoundException 類別的實例包裝進 System::SmartPtr。"
type: docs
weight: 183
url: /zh-hant/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException 類別

此例外在嘗試存取磁碟上不存在的檔案時拋出。切勿手動建立此類別的實例。請改用 FileNotFoundException 類別。切勿將 FileNotFoundException 類別的實例包裝進 [System::SmartPtr](../../system/smartptr/)。

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | 取得導致此例外的檔案名稱。 |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## 另見

* 類別 [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* 命名空間 [System::IO](../)
* 函式庫 [Aspose.Slides](../../)