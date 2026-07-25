---
title: GetInstance()
second_title: Aspose.Slides for C++ API リファレンス
description: フォーマットプロバイダーに関連付けられたフォーマッタを取得します。
type: docs
weight: 794
url: /ja/system.globalization/numberformatinfo/getinstance/
---
## NumberFormatInfo::GetInstance(const IFormatProviderPtr\&) メソッド


フォーマットプロバイダーに関連付けられたフォーマッタを取得します。

```cpp
static NumberFormatInfoPtr System::Globalization::NumberFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | フォーマットを取得するためのプロバイダー。 |

### 戻り値

フォーマットプロバイダーに関連付けられた Formatter、または利用できない場合は現在のスレッドのフォーマットを返します。

## 参照

* 型定義 [NumberFormatInfoPtr](../../numberformatinfoptr/)
* 型定義 [IFormatProviderPtr](../../../system/iformatproviderptr/)
* クラス [NumberFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)