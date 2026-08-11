---
title: CreatePortion()
second_title: Aspose.Slides برای مرجع API C++
description: یک قسمت متن خالی ایجاد می‌کند.
type: docs
weight: 1
url: /fa/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() متد

یک قسمت متن خالی ایجاد می‌کند.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### مقدار بازگشت

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) متد

یک قسمت متن را از رشته مشخص شده ایجاد می‌کند.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | رشته. |

### مقدار بازگشت

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) متد

یک قسمت را با استفاده از دادهٔ یک قسمت مشخص ایجاد می‌کند.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | یک قسمت برای استفاده. |

### مقدار بازگشت

[Portion](../../portion/).

## مراجعه

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortion](../../iportion/)
* Class [PortionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)