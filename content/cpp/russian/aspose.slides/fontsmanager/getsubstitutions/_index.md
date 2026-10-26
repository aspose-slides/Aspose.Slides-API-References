---
title: GetSubstitutions()
second_title: Справочник API Aspose.Slides для C++
description: Получает информацию о шрифтах, которые будут заменены при рендеринге презентации.
type: docs
weight: 66
url: /ru/aspose.slides/fontsmanager/getsubstitutions/
---
## FontsManager::GetSubstitutions() метод

Получает информацию о шрифтах, которые будут заменены при рендеринге презентации.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions() override
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

## FontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) метод

Получает информацию о шрифтах, которые будут заменены при рендеринге указанных слайдов.

```cpp
System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Aspose::Slides::FontSubstitutionInfo>>> Aspose::Slides::FontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Массив индексов слайдов, для которых необходимо получить информацию о замене шрифтов, начиная с 1. |

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

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Класс [FontsManager](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)