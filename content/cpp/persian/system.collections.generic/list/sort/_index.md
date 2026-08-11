---
title: Sort()
second_title: Aspose.Slides برای مرجع API C++
description: عناصر لیست را مرتب می‌کند.
type: docs
weight: 521
url: /fa/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) متد

عناصر لیست را مرتب می‌کند.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | مقایسه‌گر مورد استفاده. |

## List::Sort() متد

عناصر لیست را با استفاده از مقایسه‌گر پیش‌فرض مرتب می‌کند.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) متد

عناصر برش لیست را مرتب می‌کند.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس شروع برش. |
| count | int | اندازه برش. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | مقایسه‌گر مورد استفاده. |

## List::Sort(Comparison\<T\>, bool) متد

عناصر لیست را مرتب می‌کند.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) برای استفاده. |

## همچنین ببینید

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IComparer](../../icomparer/)
* کلاس [List](../)
* کلاس [Comparison](../../../system/comparison/)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)