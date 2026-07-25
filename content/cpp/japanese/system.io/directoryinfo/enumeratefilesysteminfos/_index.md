---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すディレクトリに格納されているすべてのファイルとディレクトリを含む列挙可能なコレクションを返します。
type: docs
weight: 131
url: /ja/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() メソッド

現在のオブジェクトが表すディレクトリに格納されているすべてのファイルおよびディレクトリを含む列挙可能コレクションを返します。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) メソッド

現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすファイルおよびディレクトリを検索します。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のファイルおよびディレクトリの名前パターン |

### 戻り値

検索パターン **searchPattern** に一致する、見つかったファイルおよびディレクトリを表す [FileSystemInfo](../../filesysteminfo/) オブジェクトへの共有ポインタの列挙可能コレクション

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) メソッド

現在のオブジェクトが表すディレクトリ、またはそのディレクトリを根とするディレクトリツリー全体のいずれかで、指定された検索条件を満たすファイルおよびディレクトリを検索します。

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のファイルおよびディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を現在のオブジェクトが表すディレクトリのみに対して実行するか、またはそのディレクトリを根とするディレクトリツリー全体に対して実行するかを指定します |

### 戻り値

検索パターン **searchPattern** に一致する、見つかったファイルおよびディレクトリを表す [FileSystemInfo](../../filesysteminfo/) オブジェクトへの共有ポインタの列挙可能コレクション

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)