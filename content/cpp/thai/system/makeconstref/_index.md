---
title: MakeConstRef
second_title: Aspose.Slides สำหรับ API ของ C++
description: ลักษณะเพื่อทำให้ประเภททั่วไป \"const reference\" หากเป็น String หรือประเภท SmartPtr<>
type: docs
weight: 1769
url: /th/system/makeconstref/
---
## MakeConstRef struct

ลักษณะเพื่อทำให้ประเภททั่วไป "const reference" หากเป็น [String](../string/) หรือประเภท SmartPtr<> 

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)