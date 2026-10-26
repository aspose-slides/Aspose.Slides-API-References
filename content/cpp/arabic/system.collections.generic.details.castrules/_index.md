---
title: "System::Collections::Generic::Details::CastRules"
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 365
url: /ar/system.collections.generic.details.castrules/
---
## الهياكل

| الهيكل | الوصف |
| --- | --- |
| [CastType](./casttype/) | يحتوي على الدوال لتحديد نوع التحويل. |
## الدوال

| الدالة | الوصف |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يكون نوع المصدر والناتج هو نفسه. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يمكن تحويل نوع المصدر إلى نوع النتيجة ثابتاً. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما لا تكون الأنواع متماثلة ولا يمكن تحويل نوع المصدر إلى نوع النتيجة ثابتاً. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يتم تغليف نوع المصدر إلى كائن الفئة [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يتم فك تغليف نوع المصدر من كائن الفئة [Nullable](../system/nullable/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يتم تغليف نوع المصدر إلى كائن الفئة [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يتم فك تغليف نوع المصدر من كائن الفئة [Object](../system/object/). |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | يقوم بتحويل نوع المصدر إلى نوع النتيجة. يُستخدم عندما يكون التحويل غير صالح أو يكون التحويل صريحاً. |
| **bool** [IsNull](./isnull/)(T) | يتحقق من أن القيمة الممثلة هي nullptr. |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | يتحقق من أن القيمة الممثلة هي nullptr. |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | يتحقق من أن القيمة الممثلة هي nullptr. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | يتحقق من إمكانية التحويل. |