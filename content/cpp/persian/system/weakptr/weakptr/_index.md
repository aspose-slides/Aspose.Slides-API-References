---
title: WeakPtr()
second_title: مرجع API Aspose.Slides برای C++
description: یک اشاره‌گر خالی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) سازنده

یک اشاره‌گر خالی ایجاد می‌کند.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) سازنده

یک اشاره‌گر ضعیف به شیء داده شده ایجاد می‌کند.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) برای ایجاد اشاره‌گر ضعیف به |

## WeakPtr::WeakPtr(const SmartPtr_&) سازنده

یک اشاره‌گر ضعیف ایجاد می‌کند که به همان اشاره‌گری که ptr اشاره می‌کند ارجاع می‌دهد.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | اشاره‌گری برای کپی مقدار اشاره‌گر از |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) سازنده

یک اشاره‌گر ضعیف ایجاد می‌کند که به همان اشاره‌گری که x اشاره می‌کند ارجاع می‌دهد.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع اشاره‌گر منبع |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | اشاره‌گری برای کپی مقدار اشاره‌گر از |

## WeakPtr::WeakPtr(const WeakPtr_&) سازنده

یک اشاره‌گر ضعیف را با سازندهٔ کپی ایجاد می‌کند.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | اشاره‌گری برای کپی مقدار اشاره‌گر از |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) سازنده

یک اشاره‌گر ضعیف را با سازندهٔ کپی ایجاد می‌کند.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Q | نوع اشاره‌گر منبع |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | اشاره‌گری برای کپی مقدار اشاره‌گر از |

## WeakPtr::WeakPtr(SmartPtr_&&) سازنده

یک اشاره‌گر ضعیف را با سازندهٔ جابه‌جایی ایجاد می‌کند.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | اشاره‌گری برای جابه‌جایی مقدار اشاره‌گر از |

## موارد مرتبط

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)