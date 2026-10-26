---
title: BinaryReader()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリームからデータを読み取り、UTF-8 エンコーディングを使用する BinaryReader クラスのインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.io/binaryreader/binaryreader/
---
## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&) コンストラクタ

[BinaryReader](../) クラスのインスタンスを作成します。このインスタンスは、UTF-8 エンコーディングを使用して、指定されたストリームからデータを読み取ります。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 入力ストリーム |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&) コンストラクタ

[BinaryReader](../) クラスのインスタンスを作成します。このインスタンスは、指定されたストリームから指定されたエンコーディングを使用してデータを読み取ります。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 入力ストリーム |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディング |

## BinaryReader::BinaryReader(const SharedPtr\<Stream\>\&, const SharedPtr\<Text::Encoding\>\&, bool) コンストラクタ

[BinaryReader](../) クラスのインスタンスを作成します。このインスタンスは、指定されたストリームから指定されたエンコーディングを使用してデータを読み取ります。

```cpp
System::IO::BinaryReader::BinaryReader(const SharedPtr<Stream> &input, const SharedPtr<Text::Encoding> &encoding, bool leaveOpen)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 入力ストリーム |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | 使用するエンコーディング |
| leaveOpen | **bool** | 現在のオブジェクトが破棄された後に、ストリーム **input** を開いたままにするかどうかを指定します (true) の場合は開いたまま、(false) の場合は閉じます |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../stream/)
* クラス [BinaryReader](../)
* クラス [Encoding](../../../system.text/encoding/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)