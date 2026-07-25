---
title: operator=()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 92
url: /ja/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) メソッド




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) メソッド


オブジェクトをこの値タプルに分解します。

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | 分解するオブジェクト |

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [ValueTuple](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)