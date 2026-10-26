---
title: GetSubstitutions()
second_title: Aspose.Slides для C++: справочник API
description: Получает информацию о шрифтах, которые будут заменены при рендеринге презентации.
type: docs
weight: 66
url: /ru/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() метод


Получает информацию о шрифтах, которые будут заменены при рендеринге презентации.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### Возвращаемое значение

Коллекция всех замен шрифтов [FontSubstitutionInfo](../../fontsubstitutioninfo/).
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```




## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) метод


Получает информацию о шрифтах, которые будут заменены при рендеринге указанных слайдов.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив индексов слайдов, для которых следует получить информацию о замене шрифтов, начиная с 1. |

### Возвращаемое значение

Коллекция всех замен шрифтов ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) для указанных слайдов.
## Примечания




```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)