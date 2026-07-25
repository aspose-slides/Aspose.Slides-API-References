---
title: Create()
second_title: Aspose.Slides for C++ API リファレンス
description: カルチャー固有の比較子を作成します。
type: docs
weight: 79
url: /ja/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) method


カルチャー固有の比較子を作成します。

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 比較子を作成する対象のカルチャー。 |
| ignoreCase | **bool** | 比較子が大文字と小文字を無視すべきかどうか。 |

### 戻り値

新しく作成された比較子オブジェクトへのポインタ。

## 関連項目

* 型定義 [StringComparerPtr](../../stringcomparerptr/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [StringComparer](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)