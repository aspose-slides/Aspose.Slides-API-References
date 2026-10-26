---
title: operator<()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ให้ความหมายการเปรียบเทียบแบบน้อยก่าสำหรับคลาส SmartPtr
type: docs
weight: 235
url: /th/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const method


ให้ความหมายการเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | ประเภทของพอยน์เตอร์ที่ใช้เปรียบเทียบกับพอยน์เตอร์ปัจจุบัน |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| p | Y * | พอยน์เตอร์ที่ใช้เปรียบเทียบกับพอยน์เตอร์ปัจจุบัน |

### Return Value

True หากวัตถุที่อ้างอิงโดย [SmartPtr](../) มีค่า 'less' น้อยกว่า p และ false ในกรณีอื่น

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const method


ให้ความหมายการเปรียบเทียบแบบน้อยกว่า สำหรับคลาส [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Y | ประเภทของพอยน์เตอร์ที่ใช้เปรียบเทียบกับพอยน์เตอร์ปัจจุบัน |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | พอยน์เตอร์ที่ใช้เปรียบเทียบกับพอยน์เตอร์ปัจจุบัน |

### Return Value

True หากวัตถุที่อ้างอิงโดย [SmartPtr](../) มีค่า 'less' น้อยกว่า x และ false ในกรณีอื่น

## ดูเพิ่มเติม

* คลาส [SmartPtr](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)