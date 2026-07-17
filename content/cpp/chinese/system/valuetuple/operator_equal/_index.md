---
title: operator=()
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 92
url: /zh/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) 方法




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) 方法


将对象分解为此值元组。

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | 用于分解的对象 |

## 另见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [ValueTuple](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)