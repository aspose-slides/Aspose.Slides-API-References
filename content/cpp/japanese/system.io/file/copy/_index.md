---
title: Copy()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたファイルを指定された場所にコピーします。宛先ファイルがすでに存在する場合、上書きするかどうかのパラメータが指定されます。
type: docs
weight: 40
url: /ja/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) メソッド

指定されたファイルを指定された場所にコピーします。宛先ファイルがすでに存在する場合、パラメータで上書きするかどうかを指定します。

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | コピーするファイルのパス |
| destFileName | const [String](../../../system/string/)\& | コピーするファイルの新しい場所のパス |
| overwrite | **bool** | 既存の宛先ファイルを上書きすべき場合は true、宛先ファイルがすでに存在する場合にコピーを失敗させる場合は false |

## 参照

* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)