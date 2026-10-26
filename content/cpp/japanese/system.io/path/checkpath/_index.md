---
title: CheckPath()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパスに無効な文字が含まれているかをチェックして、パスが有効かどうかを判定します。パスに無効な文字が含まれている場合は例外がスローされます。
type: docs
weight: 209
url: /ja/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) メソッド

指定されたパスに無効な文字が含まれているかをチェックして、パスが有効かどうかを判定します。パスに無効な文字が含まれている場合は例外がスローされます。

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | チェック対象のパス |
| msg | const [String](../../../system/string/)\& | 例外オブジェクトのコンストラクタに渡すメッセージ |
| allow_empty | **bool** | 空または null の文字列を正しいパスとみなすかどうかを指定します (true は正しい、false は正しくない)。このパラメータが false で **path** が空の場合は ArgumentException がスローされます。このパラメータが false で **path** が null の場合は ArgumentNullException がスローされます |

## 参照

* クラス [String](../../../system/string/)
* クラス [Path](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)