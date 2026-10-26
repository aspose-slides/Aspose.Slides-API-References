---
title: AppendText()
second_title: Aspose.Slides for C++ API リファレンス
description: UTF-8 エンコーディングを使用して指定されたファイルにテキストを追加する StreamWriter オブジェクトを作成します。指定されたファイルが存在しない場合は、作成されます。
type: docs
weight: 27
url: /ja/system.io/file/appendtext/
---
## File::AppendText(const String\&) メソッド


[StreamWriter](../../streamwriter/) オブジェクトを作成し、UTF-8 エンコーディングを使用して指定されたファイルにテキストを追加します。指定されたファイルが存在しない場合は、作成されます。

```cpp
static StreamWriterPtr System::IO::File::AppendText(const String &path)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | 開くまたは作成するファイルのパス |

### 戻り値

指定されたファイルに関連付けられた、作成された [StreamWriter](../../streamwriter/) オブジェクトへの共有ポインタ

## 参照

* 型定義 [StreamWriterPtr](../../../system/streamwriterptr/)
* クラス [String](../../../system/string/)
* クラス [File](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)