---
title: SetByte()
second_title: مرجع API Aspose.Slides للـ C++
description: يفسر المصفوفة المكتوبة بالنوع المحدد كمصفوفة بايتات خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة للبايت.
type: docs
weight: 40
url: /ar/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) طريقة

يقوم بتفسير المصفوفة المكتوبة بالنوع المحدد كمصفوفة بايتات خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة للبايت.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المصفوفة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | المصفوفة الهدف |
| index | int | الإزاحة الصفرية للبايت الذي سيتم ضبطه |
| value | **uint8_t** | قيمة البايت التي سيتم ضبطها |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) طريقة

يقوم بتفسير المصفوفة المكتوبة بالنوع المحدد كمصفوفة بايتات خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة للبايت.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المصفوفة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | عرض المصفوفة الهدف |
| index | int | الإزاحة الصفرية للبايت الذي سيتم ضبطه |
| value | **uint8_t** | قيمة البايت التي سيتم ضبطها |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) طريقة

يقوم بتفسير المصفوفة المكتوبة بالنوع المحدد كمصفوفة بايتات خام ويضبط قيمة البايت المحددة عند الإزاحة المحددة للبايت.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع عناصر المصفوفة |
| N | حجم المصفوفة المكدسة |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | المصفوفة المكدسة الهدف |
| index | int | الإزاحة الصفرية للبايت الذي سيتم ضبطه |
| value | **uint8_t** | قيمة البايت التي سيتم ضبطها |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Array](../../array/)
* فئة [Buffer](../)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)