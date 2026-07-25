---
title: Cast()
second_title: Aspose.Slides の C++ API リファレンス
description: SmartPtr オブジェクトに対してキャストを実行します。
type: docs
weight: 2510
url: /ja/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) 関数

[SmartPtr](../smartptr/) オブジェクトに対してキャストを実行します。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TTo | 対象の指し示す型。 |
| TFrom | ソースの指し示す型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | ソース ポインタ。 |

### 戻り値

キャストが許可されている場合のキャスト結果。

## 参照

* クラス [SmartPtr](../smartptr/)
* 構造体 [IsExceptionWrapper](../isexceptionwrapper/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)