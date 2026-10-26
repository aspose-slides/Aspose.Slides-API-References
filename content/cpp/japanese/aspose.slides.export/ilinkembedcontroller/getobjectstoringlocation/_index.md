---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ APIリファレンス
description: オブジェクトを格納すべき場所を決定します。このメソッドは各オブジェクト ID ごとに一度呼び出されます。同じ data、semanticName、contentType を持ち、異なる ID のオブジェクトが存在する可能性があることは保証されません。
type: docs
weight: 1
url: /ja/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) メソッド

オブジェクトを格納すべき場所を決定します。このメソッドは各オブジェクト ID ごとに一度呼び出されます。同じ data、semanticName、contentType を持ち、異なる ID のオブジェクトが存在する可能性があることは保証されません。

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| id | **int32_t** | オブジェクト ID。 この ID は保存操作全体で一意です。 |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | オブジェクトのバイナリ データ。オブジェクトのバイナリ データがまだ生成されていない場合、このパラメータは null になる可能性があります。 |
| semanticName | [System::String](../../../system/string/) | オブジェクトの意味を示す短いテキスト。コントローラはこれを外部オブジェクト名の一部として使用することがありますが、名前が一意で許可された文字のみを含むことを保証するのはディスパッチャの責任です。 |
| contentType | [System::String](../../../system/string/) | オブジェクトの MIME タイプ。 |
| recomendedExtension | [System::String](../../../system/string/) | この MIME タイプに推奨されるファイル名拡張子。 |

### 戻り値

Decision

## 参照

* 列挙型 [LinkEmbedDecision](../../linkembeddecision/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [ILinkEmbedController](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)