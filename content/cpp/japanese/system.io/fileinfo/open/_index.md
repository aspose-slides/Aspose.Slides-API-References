---
title: Open()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すファイルを、指定されたモードで読み取りおよび書き込み用に、共有なしで開きます。
type: docs
weight: 183
url: /ja/system.io/fileinfo/open/
---
## FileInfo::Open(FileMode) メソッド

現在のオブジェクトが表すファイルを、指定されたモードで読み取りおよび書き込み用に、共有なしで開きます。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します |

### 戻り値

現在のオブジェクトが表すファイルに関連付けられた [FileStream](../../filestream/) オブジェクト

## FileInfo::Open(FileMode, FileAccess) メソッド

現在のオブジェクトが表すファイルを、指定されたモードとアクセス種別で、共有なしで開きます。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します |
| access | [FileAccess](../../fileaccess/) | 要求されたアクセス種別 |

### 戻り値

現在のオブジェクトが表すファイルに関連付けられた [FileStream](../../filestream/) オブジェクト

## FileInfo::Open(FileMode, FileAccess, FileShare) メソッド

現在のオブジェクトが表すファイルを、指定されたモード、アクセス種別、共有オプションで開きます。

```cpp
FileStreamPtr System::IO::FileInfo::Open(FileMode mode, FileAccess access, FileShare share)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [FileMode](../../filemode/) | ファイルを開くモードを指定します |
| access | [FileAccess](../../fileaccess/) | 要求されたアクセス種別 |
| share | [FileShare](../../fileshare/) | 他の [FileStream](../../filestream/) オブジェクトが開かれたファイルに対して持つアクセスの種類 |

### 戻り値

現在のオブジェクトが表すファイルに関連付けられた [FileStream](../../filestream/) オブジェクト

## 関連項目

* 列挙型 [FileMode](../../filemode/)
* 列挙型 [FileAccess](../../fileaccess/)
* 列挙型 [FileShare](../../fileshare/)
* 型定義 [FileStreamPtr](../../../system/filestreamptr/)
* クラス [FileInfo](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)