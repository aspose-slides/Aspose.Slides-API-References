---
title: GetFileSystemInfos()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すディレクトリ内にあるすべてのファイルおよびディレクトリを表す FileSystemInfo オブジェクトへの共有ポインタを含む配列を返します。
type: docs
weight: 170
url: /ja/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() メソッド


現在のオブジェクトが表すディレクトリ内にあるすべてのファイルおよびディレクトリを表す [FileSystemInfo](../../filesysteminfo/) オブジェクトへの共有ポインタを含む配列を返します。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) メソッド


現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルおよびディレクトリを検索します。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のファイルおよびディレクトリの名前パターン |

### 戻り値

名前が **searchPattern** と一致する、見つかったファイルおよびディレクトリを表す [FileSystemInfo](../../filesysteminfo/) オブジェクトへの共有ポインタの配列

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) メソッド


現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとするディレクトリツリー全体のいずれかで、指定された検索条件を満たすファイルおよびディレクトリを検索します。

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のファイルおよびディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を現在のオブジェクトが表すディレクトリのみで実行するか、またはそのディレクトリをルートとするディレクトリツリー全体で実行するかを指定します |

### 戻り値

名前が **searchPattern** と一致する、見つかったファイルおよびディレクトリを表す [FileSystemInfo](../../filesysteminfo/) オブジェクトへの共有ポインタの配列

## 参照

* 列挙型 [SearchOption](../../searchoption/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* クラス [DirectoryInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)