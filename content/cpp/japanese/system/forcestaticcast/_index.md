---
title: ForceStaticCast()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartPtr オブジェクトに対して実際の static cast を実行します。
type: docs
weight: 2588
url: /ja/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) 関数


[SmartPtr](../smartptr/) オブジェクトに対して実際の static cast を実行します。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | ターゲット ポインティー タイプ。 |
| TFrom | ソース ポインティー タイプ。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合はキャスト結果を返し、そうでない場合は動作は未定義です。

## 参照

* クラス [SmartPtr](../smartptr/)
* 構造体 [CastResult](../castresult/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)