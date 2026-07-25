---
title: EnumerateDirectories()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを含む列挙可能なコレクションを返します。
type: docs
weight: 105
url: /ja/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() メソッド

現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを含む列挙可能なコレクションを返します。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) メソッド

現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすディレクトリを検索します。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のディレクトリの名前パターン |

### 戻り値

検索パターン **searchPattern** に一致する名前を持つ、見つかったディレクトリを表す [DirectoryInfo](../) オブジェクトへの共有ポインタの列挙可能なコレクション

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) メソッド

現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとするディレクトリツリー全体のいずれかで、指定された検索条件を満たすディレクトリを検索します。

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を現在のオブジェクトが表すディレクトリのみで実行するか、あるいはそのディレクトリをルートとするディレクトリツリー全体で実行するかを指定します |

### 戻り値

検索パターン **searchPattern** に一致する名前を持つ、見つかったディレクトリを表す [DirectoryInfo](../) オブジェクトへの共有ポインタの列挙可能なコレクション

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)