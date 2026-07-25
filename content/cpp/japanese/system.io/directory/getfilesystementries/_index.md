---
title: GetFileSystemEntries()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたディレクトリ、またはそのディレクトリをルートとするディレクトリツリー全体において、指定された検索条件を満たすファイルおよびディレクトリを検索します。
type: docs
weight: 92
url: /ja/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) メソッド

指定されたディレクトリ、またはそのディレクトリをルートとするディレクトリツリー全体において、指定された検索基準を満たすファイルとディレクトリを検索します。

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 検索対象ディレクトリへのフルパスまたは相対パス |
| searchPattern | const [String](../../../system/string/)\& | 検索対象のファイルおよびディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を指定されたディレクトリだけで実行するか、指定されたディレクトリをルートとするディレクトリツリー全体で実行するかを指定します |

### 戻り値

検索パターン **searchPattern** に一致する、見つかったファイルおよびディレクトリのフルパスの配列

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [Directory](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)