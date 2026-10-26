---
title: ReplaceFont()
second_title: Aspose.Slides для C++ – справочник API
description: Заменить шрифт в презентации
type: docs
weight: 118
url: /ru/aspose.slides/fontsmanager/replacefont/
---
## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontData\>, System::SharedPtr\<Aspose::Slides::IFontData\>) метод

Заменить шрифт в презентации

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontData> sourceFont, System::SharedPtr<Aspose::Slides::IFontData> destFont) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Исходный шрифт |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontData](../../ifontdata/)\> | Шрифт назначения |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRule\>) метод

Заменить шрифт в презентации, используя информацию, предоставленную в [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRule> substRule) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRule](../../ifontsubstrule/)\> | Информация о замене шрифта |

## FontsManager::ReplaceFont(System::SharedPtr\<Aspose::Slides::IFontSubstRuleCollection\>) метод

Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [FontSubstRule](../../fontsubstrule/)

```cpp
void Aspose::Slides::FontsManager::ReplaceFont(System::SharedPtr<Aspose::Slides::IFontSubstRuleCollection> substRules) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Коллекция правил замены шрифтов |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IFontData](../../ifontdata/)
* Класс [FontsManager](../)
* Класс [IFontSubstRule](../../ifontsubstrule/)
* Класс [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)