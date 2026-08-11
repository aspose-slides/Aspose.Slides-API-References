---
title: CreatePortion()
second_title: مرجع API Aspose.Slides برای C++
description: یک بخش متن خالی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() متد


یک بخش متن خالی ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### مقدار بازگشت

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) متد


یک بخش متن را از رشتهٔ مشخص شده ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | رشته. |

### مقدار بازگشت

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) متد


یک بخش را با استفاده از دادهٔ بخش مشخص‌شده ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | بخشی که استفاده می‌شود. |

### مقدار بازگشت

[Portion](../../portion/).

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [IPortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)