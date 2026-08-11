---
title: GetSubstitutions()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض العرض التقديمي.
type: docs
weight: 66
url: /ar/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() طريقة

يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض العرض التقديمي.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### قيمة الإرجاع

مجموعة من جميع استبدالات الخطوط [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) طريقة

يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض الشرائح المحددة.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة من فهارس الشرائح التي يجب استرجاع معلومات استبدال الخطوط لها، بدءًا من 1. |

### قيمة الإرجاع

مجموعة من جميع استبدالات الخطوط ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) للشرائح المحددة.

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* فئة [IFontsManager](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)