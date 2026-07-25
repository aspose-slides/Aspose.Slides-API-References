---
title: Replace()
second_title: Aspose.Slides for C++ API リファレンス
description: あるファイルの内容を別のファイルに置き換え、置き換えられたファイルのバックアップを作成します。
type: docs
weight: 339
url: /ja/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) メソッド

一つのファイルの内容を別のファイルに置き換え、置き換えられたファイルのバックアップを作成します。

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | 置き換えるファイルの名前 |
| destinationFileName | const [String](../../../system/string/)\& | 置き換えられるファイルの名前 |
| destinationBackupFileName | const [String](../../../system/string/)\& | バックアップファイルの名前 |
| ignoreMetadataErrors | **bool** | 置き換えられたファイルから新しいファイルへのマージエラーを無視するかどうかを指定します（true の場合は無視し、false の場合は無視しません）。 |

## 参照

* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)