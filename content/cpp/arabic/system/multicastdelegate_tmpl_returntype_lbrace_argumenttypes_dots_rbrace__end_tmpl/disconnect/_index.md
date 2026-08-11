---
title: disconnect()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل المفوض المحدد من مجموعة المفوضين.
type: docs
weight: 170
url: /ar/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) طريقة


يزيل المفوض المحدد من مجموعة المفوضين.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [Callback](../callback/) | المفوض الذي سيتم إزالته من المجموعة |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) طريقة


يزيل الطريقة غير الثابتة المحددة للكائن المحدد من مجموعة المفوضين.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| MemberType | نوع الطريقة غير الثابتة التي سيتم إزالتها من مجموعة المفوضين |
| ClassType | نوع الكائن الذي تنتمي إليه الطريقة غير الثابتة التي سيتم إزالتها من مجموعة المفوضين |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| member | MemberType ClassType::* | مؤشر إلى الطريقة غير الثابتة للكائن المحدد |
| obj | ClassType * | مؤشر إلى طريقة عضو الكائن التي سيتم إزالتها من مجموعة المفوضين |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) طريقة


يزيل الطريقة غير الثابتة المحددة للكائن المحدد من مجموعة المفوضين.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| MemberType | نوع الطريقة غير الثابتة التي سيتم إزالتها من مجموعة المفوضين |
| ClassType | نوع الكائن الذي تنتمي إليه الطريقة غير الثابتة التي سيتم إزالتها من مجموعة المفوضين |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| member | MemberType ClassType::* | مؤشر إلى الطريقة غير الثابتة للكائن المحدد |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | مؤشر مشترك إلى طريقة عضو كائن سيتم إزالتها من مجموعة المفوضين |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) طريقة


يزيل كائن MulticastDelegate المحدد من مجموعة المفوضين.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | مثيل من فئة MulticastDelegate لإزالته من مجموعة المفوضين |

### قيمة الإرجاع

مرجع إلى الكائن نفسه

## انظر أيضًا

* تعريف النوع [Callback](../callback/)
* تعريف النوع [SharedPtr](../../sharedptr/)
* طريقة [MulticastDelegate](../multicastdelegate/)
* فئة [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)