---
title: operator<()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartPtr クラスに対して less-compare のセマンティクスを提供します。
type: docs
weight: 235
url: /ja/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const メソッド

[SmartPtr](../) クラスに対して less-compare のセマンティクスを提供します。

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | Type of pointer to compare current one to. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| p | Y * | Pointer to compare current one to. |

### 戻り値

True if the object referenced by [SmartPtr](../) is 'less' than p and false otherwise.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const メソッド

[SmartPtr](../) クラスに対して less-compare のセマンティクスを提供します。

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | Type of pointer to compare current one to. |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | Pointer to compare current one to. |

### 戻り値

True if the object referenced by [SmartPtr](../) is 'less' than x and false otherwise.

## 参照

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)