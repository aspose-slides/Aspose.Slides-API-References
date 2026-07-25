---
title: GetInstance()
second_title: Aspose.Slides for C++ API リファレンス
description: フォーマットプロバイダーに関連付けられたフォーマッタを取得します。
type: docs
weight: 846
url: /ja/system.globalization/datetimeformatinfo/getinstance/
---
## DateTimeFormatInfo::GetInstance(const IFormatProviderPtr\&) メソッド

フォーマットプロバイダーに関連付けられたフォーマッタを取得します。

```cpp
static DateTimeFormatInfoPtr System::Globalization::DateTimeFormatInfo::GetInstance(const IFormatProviderPtr &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | フォーマットを取得するプロバイダー。 |

### 戻り値

フォーマットプロバイダーに関連付けられたフォーマッタ、または利用できない場合は現在のスレッドのフォーマット。

## 参照

* Typedef [DateTimeFormatInfoPtr](../../datetimeformatinfoptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* クラス [DateTimeFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)