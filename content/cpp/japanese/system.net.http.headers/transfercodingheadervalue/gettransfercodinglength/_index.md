---
title: GetTransferCodingLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を TransferCodingHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 105
url: /ja/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) メソッド

指定されたインデックスから渡された文字列を [TransferCodingHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | [TransferCodingHeaderValue](../) クラスのインスタンスを作成するために使用されるデリゲート。 |

### 戻り値

解析されたサブ文字列の長さを返します。そうでなければ 0 を返します。

## 参照

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)