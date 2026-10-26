---
title: FindHeader()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたヘッダー タイプでヘッダー マッピングを検索します。
type: docs
weight: 352
url: /ja/system.web.services.protocols/soapmessage/findheader/
---
## SoapMessage::FindHeader(System::ArrayPtr\<System::SharedPtr\<SoapHeaderMapping\>\>, const TypeInfo\&) メソッド


指定されたヘッダー タイプでヘッダー マッピングを検索します。

```cpp
System::SharedPtr<SoapHeaderMapping> System::Web::Services::Protocols::SoapMessage::FindHeader(System::ArrayPtr<System::SharedPtr<SoapHeaderMapping>> headersInfo, const TypeInfo &headerType)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| headersInfo | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<SoapHeaderMapping\>\> | ヘッダー マッピングのコレクション。 |
| headerType | const [TypeInfo](../../../system/typeinfo/)\& | 検索対象のヘッダー タイプ。 |

### 戻り値

ヘッダー マッピング。

## 参照項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [TypeInfo](../../../system/typeinfo/)
* クラス [SoapMessage](../)
* 名前空間 [System::Web::Services::Protocols](../../)
* ライブラリ [Aspose.Slides](../../../)