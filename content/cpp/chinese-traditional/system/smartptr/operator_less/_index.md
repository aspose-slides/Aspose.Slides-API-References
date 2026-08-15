---
title: operator<()
second_title: Aspose.Slides for C++ API 參考文件
description: 提供 SmartPtr 類別的較小比較語意。
type: docs
weight: 235
url: /zh-hant/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method

Provides less-compare semantics for [SmartPtr](../) class.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Y | 欲比較之指標的類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| p | Y * | 指向欲比較的指標。 |

### 回傳值

如果 [SmartPtr](../) 所參照的物件比 p 『較小』，則回傳 true；否則回傳 false。

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method

Provides less-compare semantics for [SmartPtr](../) class.

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Y | 欲比較之指標的類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | 指向欲比較的指標。 |

### 回傳值

如果 [SmartPtr](../) 所參照的物件比 x『較小』，則回傳 true；否則回傳 false。

## 另請參閱

* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)