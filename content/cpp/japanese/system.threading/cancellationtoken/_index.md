---
title: CancellationToken
second_title: Aspose.Slides for C++ API リファレンス
description: 操作がキャンセルされるべきであることを通知します。このクラスはスレッド間の協調的なキャンセルのためのメカニズムを提供し、あるスレッドが操作のキャンセルを他のスレッドに通知できるようにします。
type: docs
weight: 14
url: /ja/system.threading/cancellationtoken/
---
## CancellationToken クラス


操作がキャンセルされるべきであることを通知します。このクラスはスレッド間の協調的なキャンセルのためのメカニズムを提供し、あるスレッドが操作のキャンセルを他のスレッドに通知できるようにします。

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | デフォルトコンストラクタ。 |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | このトークンがキャンセルされた状態になることができるかどうかを取得します。 |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | このトークンに対してキャンセルが要求されたかどうかを取得します。 |
| static [CancellationToken](./) [get_None](./get_none/)() | 空の [System::Threading::CancellationToken](./) 値を返します。 |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | キャンセルが要求されたときに呼び出されるコールバックを登録します。 |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | キャンセルが要求された場合、OperationCanceledException をスローします。 |
## 備考



[CancellationToken](./) は、その関連付けられた [CancellationTokenSource](../cancellationtokensource/) を介してのみキャンセルできます。 

## 参照

* 名前空間 [System::Threading](../)
* ライブラリ [Aspose.Slides](../../)