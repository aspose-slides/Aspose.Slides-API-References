---
title: GetFiles()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すディレクトリ内に位置するすべてのディレクトリを表す FileInfo オブジェクトへの共有ポインタを含む配列を返します。
type: docs
weight: 157
url: /ja/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() メソッド

現在のオブジェクトが表すディレクトリ内に位置するすべてのディレクトリを表す [FileInfo](../../fileinfo/) オブジェクトへの共有ポインタを含む配列を返します。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) メソッド

現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルを検索します。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象ファイルの名前パターン |

### 戻り値

検索パターン **searchPattern** に一致する名前を持つ、見つかったファイルを表す [FileInfo](../../fileinfo/) オブジェクトへの共有ポインタを含む配列

## DirectoryInfo::GetFiles(const String\&, SearchOption) メソッド

現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとする全ディレクトリツリー内で、指定された検索条件を満たすファイルを検索します。

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象ファイルの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を現在のオブジェクトが表すディレクトリのみに限定するか、またはそのディレクトリをルートとする全ディレクトリツリーで実行するかを指定します |

### 戻り値

検索パターン **searchPattern** に一致する名前を持つ、見つかったファイルを表す [FileInfo](../../fileinfo/) オブジェクトへの共有ポインタを含む配列

## 参照

* 列挙体 [SearchOption](../../searchoption/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [FileInfoPtr](../../../system/fileinfoptr/)
* クラス [DirectoryInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)