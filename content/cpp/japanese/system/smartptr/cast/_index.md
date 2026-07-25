---
title: Cast()
second_title: Aspose.Slides for C++ API リファレンス
description: ポインタをその型自身にキャストします。
type: docs
weight: 287
url: /ja/system/smartptr/cast/
---
## SmartPtr::Cast() const method

ポインタをその型自身にキャストします。

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### 戻り値

常に共有モードである、変更された型のポインタです。

## SmartPtr::Cast() const method

static_cast を使用してポインタを基底型にキャストします。

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### 戻り値

常に共有モードである、変更された型のポインタです。

## SmartPtr::Cast() const method

dynamic_cast を使用してポインタを派生型にキャストします。

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### 戻り値

常に共有モードである、変更された型のポインタです。変換が利用できない場合は InvalidCastException をスローします。

## SmartPtr::Cast() const method

dynamic_cast を使用してポインタを派生型にキャストします。

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | Target type of pointed object. |
| Check | Flags to throw exception if no cast available. |

### 戻り値

常に共有モードである、変更された型のポインタです。変換が利用できない場合は nullptr を返します。

## 関連項目

* クラス [SmartPtr](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)