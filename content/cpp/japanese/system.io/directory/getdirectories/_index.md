---
title: GetDirectories()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたディレクトリ、または指定されたディレクトリをルートとするディレクトリツリー全体で、指定された検索条件を満たすディレクトリを検索します。
type: docs
weight: 66
url: /ja/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String&, const String&, SearchOption) メソッド

指定されたディレクトリ、または指定されたディレクトリをルートとするディレクトリツリー全体の中で、指定された検索条件を満たすディレクトリを検索します。

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 検索対象ディレクトリへのフルパスまたは相対パス |
| searchPattern | const [String](../../../system/string/)\& | 検索対象ディレクトリの名前パターン |
| searchOption | [SearchOption](../../searchoption/) | 検索を指定ディレクトリのみで実行するか、指定ディレクトリをルートとしたディレクトリツリー全体で実行するかを指定します |

### 戻り値

searchPattern に一致する見つかったディレクトリのフルパスの配列

## 参照

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [Directory](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)