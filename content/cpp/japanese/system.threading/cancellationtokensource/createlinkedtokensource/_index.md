---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides for C++ API リファレンス
description: 提供されたトークンのいずれかがキャンセルされると、リンクされたトークン ソースがキャンセルされます。
type: docs
weight: 66
url: /ja/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken&, const CancellationToken&) メソッド

提供されたトークンのいずれかがキャンセルされると、リンクされたトークン ソースがキャンセルされます。

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | 監視対象の最初のキャンセルトークン。 |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | 監視対象の2番目のキャンセルトークン。 |

### 戻り値

いずれかの入力トークンがキャンセルされるとキャンセルされる新しいトークン ソース。

## 備考

返されたソースは、いずれかの入力トークンがすでにキャンセルされている場合、直ちにキャンセルされます。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [CancellationTokenSource](../)
* クラス [CancellationToken](../../cancellationtoken/)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)