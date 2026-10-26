---
title: Register()
second_title: Aspose.Slides for C++ API リファレンス
description: キャンセルが要求されたときに呼び出されるコールバックを登録します。
type: docs
weight: 40
url: /ja/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const メソッド


キャンセルが要求されたときに呼び出されるコールバックを登録します。

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | キャンセルが要求されたときに実行される Action<>。 |

### 戻り値

[CancellationTokenRegistration](../../cancellationtokenregistration/) オブジェクトで、コールバックの登録解除に使用できます。

## 備考



キャンセルがすでに要求されている場合、コールバックは直ちに呼び出されます。 

コールバックは短時間でブロッキングしないようにすべきです。これは [CancellationTokenSource](../../cancellationtokensource/) の Cancel() を呼び出すスレッド上で実行されるためです。 

## 関連項目

* Typedef [Action](../../../system/action/)
* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)