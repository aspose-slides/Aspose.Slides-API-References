---
title: operator=()
second_title: Aspose.Slides for C++ API 參考文件
description: 
type: docs
weight: 92
url: /zh-hant/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) 方法




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) 方法


將物件解構為此值元組。

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | 要解構的物件 |

## 另見

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [ValueTuple](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)