---
title: ConvertAll()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء جدید Array می‌سازد و آن را با عناصری از آرایهٔ مشخص شده که با استفاده از نمایندهٔ مبدل تعیین‌شده به نوع OutputType تبدیل شده‌اند، پر می‌کند.
type: docs
weight: 625
url: /fa/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) متد

یک شیء جدید [Array](../) را می‌سازد و آن را با عناصری از آرایهٔ مشخص شده که به نوع **OutputType** تبدیل شده‌اند، با استفاده از نمایندهٔ مبدل مشخص‌شده پر می‌کند.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| InputType | نوع عناصر آرایهٔ ورودی |
| OutputType | نوع عناصر آرایهٔ خروجی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | یک شیء [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | یک شیء Converter که برای تبدیل هر عنصر آرایهٔ ورودی به مقادیر معادل نوع **OutputType** استفاده می‌شود |

### مقدار بازگشت

یک آرایهٔ جدید حاوی مقادیر نوع **OutputType** که معادل مقادیر **input_array** هستند

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) متد

یک شیء جدید [Array](../) را می‌سازد و آن را با عناصری از آرایهٔ مشخص شده که به نوع **OutputType** تبدیل شده‌اند، با استفاده از شیء تابع مبدل مشخص‌شده پر می‌کند.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| InputType | نوع عناصر آرایهٔ ورودی |
| OutputType | نوع عناصر آرایهٔ خروجی |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | یک شیء [Array](../) |
| converter | std::function\<OutputType(InputType)> | یک شیء تابع که برای تبدیل هر عنصر آرایهٔ ورودی به مقادیر معادل نوع **OutputType** استفاده می‌شود |

### مقدار بازگشت

یک آرایهٔ جدید حاوی مقادیر نوع **OutputType** که معادل مقادیر **input_array** هستند

## موارد مرتبط

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)