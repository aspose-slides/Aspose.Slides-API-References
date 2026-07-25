---
title: Cast_noexcept()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartPtr オブジェクトに対してキャストを実行します。
type: docs
weight: 2497
url: /ja/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) 関数

[SmartPtr](../smartptr/) オブジェクトに対してキャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象ポインタ先の型。 |
| TFrom | 元のポインタ先の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されていればキャスト結果を、そうでなければ nullptr を返します。

## 参照

* クラス [SmartPtr](../smartptr/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)