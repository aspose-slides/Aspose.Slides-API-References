---
title: StaticCastArray()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفّذ تحويل عناصر المصفوفة المحددة إلى نوع مختلف. يُستخدم كإلغاء للحالات التي يكون فيها From هو كائن SmartPtr.
type: docs
weight: 2978
url: /ar/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) دالة

ينفّذ تحويل عناصر المصفوفة المحددة إلى نوع مختلف. تجاوز للحالات التي يكون فيها From هو [SmartPtr](../smartptr/) كائن.

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| To | النوع الذي يتم تحويل عناصر المصفوة المحددة إليه |
| From | نوع عناصر العناصر من المصفوفة التي يتم التحويل منها |

### المعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | مؤشر مشترك إلى المصفوفة التي تحتوي على العناصر المراد تحويلها |

### قيمة الإرجاع

مؤشر إلى مصفوفة جديدة تحتوي على عناصر من النوع **To** مساوية لعناصر **from**

مهمل
:   تمت الإضافة للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) دالة

ينفّذ تحويل عناصر المصفوفة المحددة إلى نوع مختلف. تجاوز للحالات التي يكون فيها From هو Boxable و To هو [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```

### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| To | النوع الذي يتم تحويل عناصر المصفوة المحددة إليه |
| From | نوع عناصر العناصر من المصفوفة التي يتم التحويل منها |

### المعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | مؤشر مشترك إلى المصفوفة التي تحتوي على العناصر المراد تحويلها |

### قيمة الإرجاع

مؤشر إلى مصفوفة جديدة تحتوي على عناصر من النوع **To** مساوية لعناصر **from**

مهمل
:   تمت الإضافة للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## انظر أيضًا

* تعريف نوع [SharedPtr](../sharedptr/)
* فئة [Array](../array/)
* فئة [Object](../object/)
* بنية [IsSmartPtr](../issmartptr/)
* بنية [IsBoxable](../isboxable/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)