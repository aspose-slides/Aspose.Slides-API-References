---
title: IFontsManager
second_title: Aspose.Sildes для .NET API Reference
description: Управляет шрифтами в презентации.
type: docs
weight: 5730
url: /ru/aspose.slides/ifontsmanager/
---

## Интерфейс IFontsManager

Управляет шрифтами в презентации.

```csharp
public interface IFontsManager
```

## Свойства

| Имя | Описание |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/ifontsmanager/fontfallbackrulescollection) { get; set; } | Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов для правильной замены с помощью функции резервирования Чтение/запись [`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/ifontsmanager/fontsubstrulelist) { get; set; } | Замены шрифтов, которые следует использовать при рендеринге Чтение/запись [`IFontSubstRuleCollection`](../ifontsubstrulecollection). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/ifontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Добавляет встроенный шрифт Имейте в виду, что при добавлении любых шрифтов большинство шрифтов защищены авторским правом. Сначала найдите лицензию на шрифт заранее и убедитесь, что его можно свободно перенести на другой компьютер. Может возникнуть исключение ArgumentException, если данные шрифта равны null или этот шрифт уже встроен. |
| [AddEmbeddedFont](../../aspose.slides/ifontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Добавляет встроенный шрифт. Имейте в виду, что при копировании любых шрифтов большинство шрифтов защищены авторским правом. Сначала найдите лицензию на шрифт заранее и убедитесь, что его можно свободно перенести на другой компьютер. Может возникнуть исключение ArgumentException, если данные шрифта равны null или этот шрифт уже встроен. |
| [GetEmbeddedFonts](../../aspose.slides/ifontsmanager/getembeddedfonts)() | Возвращает шрифты, встроенные в презентацию. |
| [GetFontBytes](../../aspose.slides/ifontsmanager/getfontbytes)(IFontData, FontStyle) | Извлекает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта. |
| [GetFontEmbeddingLevel](../../aspose.slides/ifontsmanager/getfontembeddinglevel)(byte[], string) | Определяет уровень встраивания шрифта из указанного массива байтов и имени шрифта. |
| [GetFonts](../../aspose.slides/ifontsmanager/getfonts)() | Возвращает шрифты, используемые в презентации. |
| [GetSubstitutions](../../aspose.slides/ifontsmanager/getsubstitutions)() | Получает информацию о шрифтах, которые будут заменены при рендеринге презентации. |
| [RemoveEmbeddedFont](../../aspose.slides/ifontsmanager/removeembeddedfont)(IFontData) | Удаляет встроенный шрифт. |
| [ReplaceFont](../../aspose.slides/ifontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Заменяет шрифт в презентации, используя информацию, предоставленную в [`IFontSubstRule`](../ifontsubstrule). |
| [ReplaceFont](../../aspose.slides/ifontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Заменяет шрифт в презентации, используя информацию, предоставленную в коллекции [`IFontSubstRule`](../ifontsubstrule). |
| [ReplaceFont](../../aspose.slides/ifontsmanager/replacefont#replacefont)(IFontData, IFontData) | Заменяет шрифт в презентации. |

### Смотрите также

* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->