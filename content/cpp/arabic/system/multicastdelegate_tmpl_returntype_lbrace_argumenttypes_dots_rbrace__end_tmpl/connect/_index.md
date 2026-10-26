---
title: connect()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضيف المفوض المحدد إلى التجميع.
type: docs
weight: 144
url: /ar/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) طريقة

يضيف المفوض المحدد إلى التجميع.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [Callback](../callback/) | المفوض لإضافته إلى التجميع |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) طريقة

يضيف كائن الدالة المحدد إلى مجموعة المفوضين. يتم تحويل كائن الدالة إلى نوع المفوض Callback قبل إضافته إلى المجموعة.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| R | نوع الإرجاع لكائن الدالة التي سيتم إضافتها إلى التجميع |
| Args | قائمة الوسائط لكائن الدالة التي سيتم إضافتها إلى التجميع |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| f | std::function\<R(Args...)> | كائن الدالة لإضافته إلى التجميع |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) طريقة

يضيف كائن MulticastDelegate المحدد إلى مجموعة المفوضين.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | مثال من فئة MulticastDelegate لإضافته إلى مجموعة المفوضين |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) طريقة

يضيف الطريقة غير الثابتة المحددة للكائن المحدد إلى مجموعة المفوضين.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| MemberType | نوع الطريقة غير الثابتة التي سَتُضاف إلى مجموعة المفوضين |
| ClassType | نوع الكائن الذي تنتمي إليه الطريقة التي سَتُضاف إلى مجموعة المفوضين |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| member | MemberType ClassType::* | مؤشر إلى الطريقة غير الثابتة للكائن المحدد |
| obj | ClassType * | مؤشر إلى طريقة عضو كائن تُضاف إلى مجموعة المفوضين |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) طريقة

يضيف الطريقة غير الثابتة المحددة للكائن المحدد إلى مجموعة المفوضين.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| MemberType | نوع الطريقة غير الثابتة التي سَتُضاف إلى مجموعة المفوضين |
| ClassType | نوع الكائن الذي تنتمي إليه الطريقة التي سَتُضاف إلى مجموعة المفوضين |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| member | MemberType ClassType::* | مؤشر إلى الطريقة غير الثابتة للكائن المحدد |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | مؤشر مشترك إلى طريقة عضو كائن تُضاف إلى مجموعة المفوضين |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## أنظر أيضًا

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)