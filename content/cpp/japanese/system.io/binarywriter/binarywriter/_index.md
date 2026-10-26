---
title: BinaryWriter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたエンコーディングを使用して、指定されたストリームにデータを書き込む BinaryWriter クラスのインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.io/binarywriter/binarywriter/
---
## BinaryWriter::BinaryWriter(const StreamPtr\&, const EncodingPtr\&, bool) コンストラクタ

指定されたエンコーディングを使用して、指定されたストリームにデータを書き込む [BinaryWriter](../) クラスのインスタンスを作成します。

```cpp
System::IO::BinaryWriter::BinaryWriter(const StreamPtr &stream, const EncodingPtr &encoding=System::Text::Encoding::get_UTF8Unmarked(), bool leaveopen=false)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | 出力ストリーム |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 使用するエンコーディング |
| leaveopen | **bool** | 現在のオブジェクトが破棄された後に、ストリーム **stream** を開いたままにするかどうかを指定します (true) または開かないか (false) |

## 参照

* Typedef [StreamPtr](../../../system/streamptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* クラス [BinaryWriter](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)