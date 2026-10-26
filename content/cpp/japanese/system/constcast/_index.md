---
title: ConstCast()
second_title: Aspose.Slides for C++ API リファレンス
description: 非推奨キャストの終了。
type: docs
weight: 2575
url: /ja/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) 関数

非推奨キャストの終了。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| TTo | 対象のポインテッド型。 |
| TFrom | ソースのポインテッド型。 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | ソースポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を、そうでない場合は nullptr を返します。

## 備考

[SmartPtr](../smartptr/) オブジェクトに対して const キャストを実行します。

## 関連項目

* クラス [SmartPtr](../smartptr/)
* 構造体 [CastResult](../castresult/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)