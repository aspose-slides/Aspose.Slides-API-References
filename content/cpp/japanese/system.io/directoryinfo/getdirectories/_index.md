---
title: GetDirectories()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを表す DirectoryInfo オブジェクトへの共有ポインタを含む配列を返します。
type: docs
weight: 144
url: /ja/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() method

現在のオブジェクトが表すディレクトリ内にあるすべてのディレクトリを表す [DirectoryInfo](../) オブジェクトへの共有ポインタを含む配列を返します。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) method

現在のオブジェクトが表すディレクトリ内で、指定された検索条件を満たすディレクトリを検索します。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象となるディレクトリの名前パターン |

### 戻り値

検索されたディレクトリで、名前が **searchPattern** に一致するものを表す [DirectoryInfo](../) オブジェクトへの共有ポインタの配列

## DirectoryInfo::GetDirectories(const String\&, SearchOption) method

現在のオブジェクトが表すディレクトリ、またはそのディレクトリをルートとするディレクトリツリー全体のいずれかで、指定された検索条件を満たすディレクトリを検索します。

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | 検索対象となるディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を現在のオブジェクトが表すディレクトリのみで実行するか、またはそのディレクトリをルートとするディレクトリツリー全体で実行するかを指定します |

### 戻り値

検索されたディレクトリで、名前が **searchPattern** に一致するものを表す [DirectoryInfo](../) オブジェクトへの共有ポインタの配列

## 参照

* 列挙型 [SearchOption](../../searchoption/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* クラス [DirectoryInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)