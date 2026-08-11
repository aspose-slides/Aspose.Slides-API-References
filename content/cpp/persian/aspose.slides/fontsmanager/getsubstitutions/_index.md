---
title: GetSubstitutions()
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات مربوط به قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() متد


اطلاعات مربوط به قلم‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```


### مقدار بازگشت

مجموعه‌ای از تمام جایگزینی‌های قلم [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) متد


اطلاعات مربوط به قلم‌هایی که در هنگام رندر اسلایدهای مشخص شده جایگزین خواهند شد را دریافت می‌کند.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | آرایه‌ای از ایندکس‌های اسلاید که برای آن‌ها اطلاعات جایگزینی قلم دریافت می‌شود، شروع از ۱. |

### مقدار بازگشت

مجموعه‌ای از تمام جایگزینی‌های قلم ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) برای اسلایدهای مشخص شده.
## توضیحات




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* کلاس [FontsManager](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)