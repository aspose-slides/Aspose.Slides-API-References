---
title: ReadChars()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素のテキスト内容を文字バッファに読み取ります。このメソッドは、埋め込みテキストの大きなストリームを連続して呼び出すことで読み取るように設計されています。
type: docs
weight: 755
url: /ja/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) メソッド

要素のテキスト内容を文字バッファに読み取ります。このメソッドは、埋め込みテキストの大きなストリームを連続して呼び出すことで読み取るように設計されています。

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | テキスト内容が書き込まれるバッファとして機能する文字配列。 |
| index | **int32_t** | メソッドがテキスト内容の書き込みを開始できる **buffer** 内の位置。 |
| count | **int32_t** | **buffer** に書き込む文字数。 |

### 戻り値

読み取られた文字数を返します。リーダーが要素上に位置していない場合や、現在のコンテキストで返すテキスト内容がもうない場合は 0 になることがあります。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [XmlTextReader](../)
* 名前空間 [System::Xml](../../)
* ライブラリ [Aspose.Slides](../../../)