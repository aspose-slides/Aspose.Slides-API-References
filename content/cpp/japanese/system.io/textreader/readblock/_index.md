---
title: ReadBlock()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のテキストリーダーから指定された最大文字数を読み取り、指定されたインデックスからバッファにデータを書き込みます。
type: docs
weight: 53
url: /ja/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) メソッド

現在のテキストリーダーから指定された最大文字数を読み取り、指定されたインデックスからバッファにデータを書き込みます。

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 読み取ったデータを書き込むための文字バッファ |
| index | int | 書き込みを開始する **buffer** 内の0から始まるインデックス |
| count | int | 読み取る文字数の最大値 |

### 戻り値

実際に読み取られた文字数

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [TextReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)