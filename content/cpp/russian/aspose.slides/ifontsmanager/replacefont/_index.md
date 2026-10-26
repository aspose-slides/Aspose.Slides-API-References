---
title: ReplaceFont()
second_title: Aspose.Slides для C++ справочник API
description: Заменить шрифт в презентации
type: docs
weight: 118
url: /ru/aspose.slides/ifontsmanager/replacefont/
---
## IFontsManager::ReplaceFont(System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>) метод

Заменить шрифт в презентации

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontData> sourceFont, System::SharedPtr<IFontData> destFont)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Исходный шрифт |
| destFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../ifontdata/)\> | Шрифт назначения |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRule\>) метод

Заменить шрифт в презентации, используя информацию, предоставленную в [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRule> substRule)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| substRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRule](../../ifontsubstrule/)\> | Информация о замене шрифта |

## IFontsManager::ReplaceFont(System::SharedPtr\<IFontSubstRuleCollection\>) метод

Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [IFontSubstRule](../../ifontsubstrule/)

```cpp
virtual void Aspose::Slides::IFontsManager::ReplaceFont(System::SharedPtr<IFontSubstRuleCollection> substRules)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| substRules | [System::SharedPtr](../../../system/sharedptr/)\<[IFontSubstRuleCollection](../../ifontsubstrulecollection/)\> | Коллекция информации о замене шрифта |

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IFontData](../../ifontdata/)
* Класс [IFontsManager](../)
* Класс [IFontSubstRule](../../ifontsubstrule/)
* Класс [IFontSubstRuleCollection](../../ifontsubstrulecollection/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)