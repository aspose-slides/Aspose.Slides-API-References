---
title: CreatePortion()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينشئ جزءًا نصيًا فارغًا.
type: docs
weight: 1
url: /ar/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() طريقة

ينشئ جزءًا نصيًا فارغًا.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### قيمة الإرجاع

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) طريقة

ينشئ جزءًا نصيًا من سلسلة محددة.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### معاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### قيمة الإرجاع

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) طريقة

ينشئ جزءًا باستخدام بيانات جزء محددة.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### معاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | جزء للاستخدام. |

### قيمة الإرجاع

[Portion](../../portion/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPortion](../../iportion/)
* فئة [IPortionFactory](../)
* فئة [String](../../../system/string/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)