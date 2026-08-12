---
title: Is()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ดำเนินการแปลตัวดำเนินการ 'is'. การปรับให้เหมาะสำหรับประเภทที่สามารถบรรจุได้ (value) อย่างแท้จริง.
type: docs
weight: 92
url: /th/system/objectext/is/
---
## ObjectExt::Is(const T\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทที่สามารถบรรจุได้ (value) ตามที่กำหนดไว้

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’. จะถูกละเว้น |

### ค่าที่ส่งกลับ

เสมอเป็นจริง

## ObjectExt::Is(const U\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทพอยน์เตอร์ที่ทำงานร่วมกับคลาส ‘final’

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |
| U | ประเภทที่ทดสอบ |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const U\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทพอยน์เตอร์

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |
| U | ประเภทที่ทดสอบ |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const Object\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทค่า

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const Object\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทที่ไม่สามารถแปลงได้

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เสมอคืนค่าเท็จ เนื่องจากประเภทไม่สามารถแปลงได้

## ObjectExt::Is(const SmartPtr\<U\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทพอยน์เตอร์

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทตัวห่อข้อยกเว้น

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const SmartPtr\<Object\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทที่เป็น Nullable

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const SmartPtr\<Object\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทที่สามารถบรรจุได้โดยมีตัวดำเนินการ == นิยามไว้

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const SmartPtr\<Object\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทที่สามารถบรรจุได้โดยไม่มีการนิยามตัวดำเนินการ ==

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const SmartPtr\<V\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภทค่าแบบบ็อกซ์เป็นอินเทอร์เฟซ

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |
| V | ประเภทของอ็อบเจ็กต์ที่ถูกชี้ |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const SmartPtr\<U\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภท enum

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |
| U | ประเภทของอ็อบเจ็กต์ที่ถูกชี้ |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const WeakPtr\<U\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภท enum เทียบกับ weak pointer

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |
| U | ประเภทของอ็อบเจ็กต์ที่ถูกชี้ |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) เพื่อทดสอบตัวดำเนินการ ‘is’ |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const Nullable\<U\>\&) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับประเภท [Nullable](../../nullable/)

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) ประเภท |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(const char16_t *) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับลิเตอร์ัลสตริง

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) ลิเตอร์ัล |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ObjectExt::Is(int32_t) เมธอด


ดำเนินการแปลตัวดำเนินการ ‘is’. การปรับให้เหมาะสำหรับลิเตอร์ัลจำนวนเต็ม

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### พารามิเตอร์เทมเพลต

| Parameter | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมาย |

### อาร์กิวเมนต์

| Parameter | Type | คำอธิบาย |
| --- | --- | --- |
| value | **int32_t** | ลิเตอร์ัลจำนวนเต็ม |

### ค่าที่ส่งกลับ

เป็นจริงหาก ‘is’ ให้ผลเป็นจริง, มิฉะนั้นเป็นเท็จ

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* คลาส [Object](../../object/)
* คลาส [SmartPtr](../../smartptr/)
* คลาส [ExceptionWrapper](../../exceptionwrapper/)
* คลาส [WeakPtr](../../weakptr/)
* คลาส [Nullable](../../nullable/)
* โครงสร้าง [IsBoxable](../../isboxable/)
* โครงสร้าง [IsSmartPtr](../../issmartptr/)
* โครงสร้าง [IsExceptionWrapper](../../isexceptionwrapper/)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)