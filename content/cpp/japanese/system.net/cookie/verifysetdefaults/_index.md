---
title: VerifySetDefaults()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルト属性の値を検証し、設定します。
type: docs
weight: 482
url: /ja/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) メソッド

デフォルト属性の値を検証し、設定します。

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | クッキーの仕様。 |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 内部フィールドの初期化に使用される Uri クラスのインスタンス。 |
| isLocalDomain | **bool** | クッキーがローカルドメインにプッシュされるかどうかを示す値。 |
| localDomain | [String](../../../system/string/) | ローカルドメイン名。 |
| setDefault | **bool** | クッキーの属性をデフォルト値で初期化する必要があるかどうかを示す値。 |
| shouldThrow | **bool** | 指定された値が無効な場合に例外をスローすべきかどうかを示す値。 |

### 戻り値

すべての値が有効な場合は true、そうでない場合は false。

## 参照

* 列挙型 [CookieVariant](../../cookievariant/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Uri](../../../system/uri/)
* クラス [String](../../../system/string/)
* クラス [Cookie](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)