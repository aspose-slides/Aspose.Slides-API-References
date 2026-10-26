---
title: operator=()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 92
url: /th/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) เมธอด




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) เมธอด


แยกวัตถุเป็น value tuple นี้.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Arguments

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | ออบเจ็กต์ที่จะทำการแยก |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [ValueTuple](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)