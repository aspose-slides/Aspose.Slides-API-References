---
title: FontsManager
second_title: Справочник по API Aspose.Slides для .NET
description: Управляет шрифтами во всей презентации.
type: docs
weight: 4480
url: /ru/net/aspose.slides/fontsmanager/
---
## FontsManager class

Управляет шрифтами во всей презентации.

```csharp
public class FontsManager : IFontsManager
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [FontFallBackRulesCollection](../../aspose.slides/fontsmanager/fontfallbackrulescollection) { get; set; } | Представляет пользовательскую коллекцию правил FontFallBack для управления коллекциями шрифтов для правильной замены с помощью резервной функциональности Чтение/запись[`IFontFallBackRulesCollection`](../ifontfallbackrulescollection). |
| [FontSubstRuleList](../../aspose.slides/fontsmanager/fontsubstrulelist) { get; set; } | Замена шрифта для использования при рендеринге. Чтение/запись[`IFontSubstRuleCollection`](../ifontsubstrulecollection). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont_1)(byte[], EmbedFontCharacters) | Добавляет встроенный шрифт  При копировании любых шрифтов помните, что большинство шрифтов защищены авторским правом. Сначала найдите лицензию шрифта заранее и убедитесь, что их можно свободно перенести на другую машину. ArgumentException может быть сгенерировано, если данные шрифта пусты или этот шрифт уже встроен |
| [AddEmbeddedFont](../../aspose.slides/fontsmanager/addembeddedfont#addembeddedfont)(IFontData, EmbedFontCharacters) | Добавляет встроенный шрифт  При копировании любых шрифтов помните, что большинство шрифтов защищены авторским правом. Сначала найдите лицензию шрифта заранее и убедитесь, что их можно свободно перенести на другую машину. ArgumentException может быть сгенерировано, если данные шрифта пусты или этот шрифт уже встроен |
| [GetEmbeddedFonts](../../aspose.slides/fontsmanager/getembeddedfonts)() | Возвращает встроенные в презентацию шрифты |
| [GetFonts](../../aspose.slides/fontsmanager/getfonts)() | Возвращает шрифты, использованные в презентации |
| [RemoveEmbeddedFont](../../aspose.slides/fontsmanager/removeembeddedfont)(IFontData) | Удаляет встроенный шрифт |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_1)(IFontSubstRule) | Заменить шрифт в презентации, используя информацию, предоставленную в[`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont_2)(IFontSubstRuleCollection) | Заменить шрифт в презентации, используя информацию из коллекции[`FontSubstRule`](../fontsubstrule) |
| [ReplaceFont](../../aspose.slides/fontsmanager/replacefont#replacefont)(IFontData, IFontData) | Заменить шрифт в презентации |

### Смотрите также

* interface [IFontsManager](../ifontsmanager)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->