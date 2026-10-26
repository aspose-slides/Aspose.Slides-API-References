---
title: GetFiles()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された検索条件を満たすファイルを、指定されたディレクトリまたはそのディレクトリを根とするディレクトリツリー全体から検索します。
type: docs
weight: 79
url: /ja/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) メソッド

指定された検索条件を満たすファイルを、指定されたディレクトリ内、またはそのディレクトリを根とするディレクトリツリー全体から検索します。

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 検索対象ディレクトリへのフルパスまたは相対パス |
| searchPattern | const [String](../../../system/string/)\& | 検索するファイルの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を指定ディレクトリのみで実行するか、指定ディレクトリを根とするディレクトリツリー全体で実行するかを指定します |

### 戻り値

**searchPattern** に一致する名前を持つ見つかったファイルのフルパスの配列

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [Directory](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)