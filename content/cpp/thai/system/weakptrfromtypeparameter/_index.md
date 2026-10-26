---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides สำหรับ API ของ C++
description: โครงสร้าง Trait เพื่อแปลงประเภทอาร์กิวเมนต์เป็น weak-pointer หากเป็นประเภท pointer.
type: docs
weight: 2016
url: /th/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Trait struct เพื่อแปลงประเภทอาร์กิวเมนต์ให้เป็น weak-pointer หากเป็นประเภท pointer.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)