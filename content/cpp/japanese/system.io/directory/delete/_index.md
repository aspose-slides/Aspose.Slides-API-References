---
title: Delete()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたファイルまたはディレクトリを削除します。スローしません。
type: docs
weight: 14
url: /ja/system.io/directory/delete/
---
## Directory::Delete(const String\&, bool) メソッド

指定されたファイルまたはディレクトリを削除します。スローしません。

```cpp
static void System::IO::Directory::Delete(const String &path, bool recursive=false)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 削除対象のディレクトリまたはファイルへのパス |
| recursive | **bool** | **path** が空でないディレクトリを指定している場合、**recursive** はディレクトリの内容をすべて再帰的に削除するかどうかを指定します；**path** で指定されたディレクトリが空でなく、**recursive** が 'false' の場合、操作は失敗します |

## 参照

* クラス [String](../../../system/string/)
* クラス [Directory](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)