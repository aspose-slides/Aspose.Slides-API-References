---
title: CopyTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列の文字を既存の配列要素へコピーします。サイズ変更は行われません。
type: docs
weight: 430
url: /ja/system/string/copyto/
---
## String::CopyTo(int, const ArrayPtr\<char_t\>\&, int, int) const メソッド

文字列の文字を既存の配列要素へコピーします。サイズ変更は行われません。

```cpp
void System::String::CopyTo(int sourceIndex, const ArrayPtr<char_t> &destination, int destinationIndex, int count) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceIndex | int | 文字列内で読み取りを開始するインデックス。 |
| destination | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 宛先配列。 |
| destinationIndex | int | 配列内で書き込みを開始するインデックス。 |
| count | int | コピーする文字数。 |

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)