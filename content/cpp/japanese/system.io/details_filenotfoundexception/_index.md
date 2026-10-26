---
title: Details_FileNotFoundException
second_title: Aspose.Slides for C++ API リファレンス
description: "ディスク上に存在しないファイルへのアクセスが失敗したときにスローされる例外です。このクラスのインスタンスを手動で作成しないでください。代わりに FileNotFoundException クラスを使用してください。FileNotFoundException クラスのインスタンスを System::SmartPtr にラップしないでください。"
type: docs
weight: 183
url: /ja/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException クラス

ディスク上に存在しないファイルへのアクセスが失敗したときにスローされる例外です。 このクラスのインスタンスを手動で作成しないでください。 代わりに FileNotFoundException クラスを使用してください。 FileNotFoundException クラスのインスタンスを [System::SmartPtr](../../system/smartptr/) にラップしないでください。

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## Methods

| メソッド | 説明 |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | この例外の原因となるファイル名を取得します。 |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## 参照

* クラス [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* 名前空間 [System::IO](../)
* ライブラリ [Aspose.Slides](../../)