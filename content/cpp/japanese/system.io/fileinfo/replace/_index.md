---
title: Replace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された宛先ファイルの内容を、現在の FileInfo オブジェクトで表されるファイルに置き換え、置き換えられたファイルのバックアップを作成します。
type: docs
weight: 131
url: /ja/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) メソッド

指定された宛先ファイルの内容を、現在の [FileInfo](../) オブジェクトで表されるファイルに置き換え、置き換えられたファイルのバックアップを作成します。

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 置き換えるファイルの名前 |
| destinationBackupFileName | const [String](../../../system/string/)\& | バックアップファイルの名前 |

### 戻り値

**destinationFileName** が指すファイルを表す FileInfor オブジェクトです。

## FileInfo::Replace(const String\&, const String\&, bool) メソッド

指定された宛先ファイルの内容を、現在の [FileInfo](../) オブジェクトで表されるファイルに置き換え、置き換えられたファイルのバックアップを作成します。

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | 置き換えるファイルの名前 |
| destinationBackupFileName | const [String](../../../system/string/)\& | バックアップファイルの名前 |
| ignoreMetadataErrors | **bool** | 置き換えられたファイルから置換ファイルへのマージエラーを無視するかどうかを指定します（true の場合は無視、false の場合は無視しません） |

### 戻り値

**destinationFileName** が指すファイルを表す FileInfor オブジェクトです。

## 参照

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* クラス [String](../../../system/string/)
* クラス [FileInfo](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)