---
title: GetSubstitutions()
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعات مربوط به فونت‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() متد

اطلاعات مربوط به فونت‌هایی که در رندر ارائه جایگزین خواهند شد را دریافت می‌کند.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### مقدار بازگشت

مجموعه‌ای از تمام جایگزینی فونت‌ها [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## نکات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) متد

اطلاعات مربوط به فونت‌هایی که در حین رندر اسلایدهای مشخص‌شده جایگزین می‌شوند را دریافت می‌کند.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | یک آرایه از شاخص‌های اسلایدها که اطلاعات جایگزینی فونت برای آنها بازیابی می‌شود، از 1 شروع می‌شود. |

### مقدار بازگشت

یک مجموعه از تمام جایگزینی‌های فونت ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) برای اسلایدهای مشخص‌شده.

## نکات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## مشاهده کنید

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)