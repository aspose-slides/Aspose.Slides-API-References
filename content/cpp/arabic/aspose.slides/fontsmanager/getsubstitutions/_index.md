---
title: GetSubstitutions()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على المعلومات حول الخطوط التي سيتم استبدالها أثناء عرض العرض التقديمي.
type: docs
weight: 66
url: /ar/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() طريقة

يحصل على المعلومات حول الخطوط التي ستُستبدَل أثناء عرض العرض التقديمي.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
```

### قيمة الإرجاع

مجموعة جميع استبدالات الخطوط [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) طريقة

يحصل على المعلومات حول الخطوط التي ستُستبدَل أثناء عرض الشرائح المحددة.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### معلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | مصفوفة من مؤشرات الشرائح التي يجب استرجاع معلومات استبدال الخطوط لها، بدءًا من 1. |

### قيمة الإرجاع

مجموعة جميع استبدالات الخطوط ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) للشرائح المحددة.
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
* الفئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* الفئة [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* الفئة [FontsManager](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)