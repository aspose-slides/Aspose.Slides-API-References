---
title: EnumerateFiles()
second_title: Aspose.Slides for C++ APIリファレンス
description: 現在のオブジェクトが表すディレクトリ内にあるすべてのファイルを含む列挙可能なコレクションを返します。
type: docs
weight: 118
url: /ja/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() メソッド


現在のオブジェクトが表すディレクトリ内にあるすべてのファイルを含む列挙可能なコレクションを返します。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) メソッド


現在のオブジェクトが表すディレクトリで、指定された検索条件を満たすファイルを検索します。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索するファイルの名前パターン |

### 戻り値

**searchPattern** と一致する名前を持つ、見つかったファイルを表す [FileInfo](../../fileinfo/) オブジェクトへの共有ポインターの列挙可能なコレクション

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) メソッド


現在のオブジェクトが表すディレクトリ、またはそのディレクトリを根とするディレクトリツリー全体で、指定された検索条件を満たすファイルを検索します。

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索するファイルの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 現在のオブジェクトが表すディレクトリ内のみで検索するか、ルートディレクトリからなるツリー全体で検索するかを指定します |

### 戻り値

**searchPattern** と一致する名前を持つ、見つかったファイルを表す [FileInfo](../../fileinfo/) オブジェクトへの共有ポインターの列挙可能なコレクション

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)