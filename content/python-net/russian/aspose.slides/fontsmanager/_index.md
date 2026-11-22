---
title: FontsManager class
second_title: Aspose.Slides для Python через .NET Справка API
description: 
type: docs
url: /ru/aspose.slides/fontsmanager/
---
## FontsManager класс

Управляет шрифтами во всей презентации.

Тип FontsManager раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ru/aspose.slides/fontsmanager/font_subst_rule_list/) | Замены шрифтов, используемые при рендеринге.<br/>            Чтение/запись [`IFontSubstRuleCollection`](/slides/python-net/ru/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ru/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Представляет коллекцию правил FontFallBack пользователя для управления коллекциями шрифтов для корректных замен с помощью функции fallback.<br/>            Чтение/запись [`IFontFallBackRulesCollection`](/slides/python-net/ru/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/ru/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Указывает, следует ли отдавать предпочтение зарегистрированным шрифтам перед встраиваемыми шрифтами с тем же именем и стилем.<br/>            Если включено, соответствующие встраиваемые шрифты временно заменяются соответствующими зарегистрированными шрифтами при экспорте. |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ru/aspose.slides/fontsmanager/get_substitutions/#) | Получает информацию о шрифтах, которые будут заменены при рендеринге презентации. |
| [`get_substitutions(self, slides)`](/slides/python-net/ru/aspose.slides/fontsmanager/get_substitutions/#listint) | Получает информацию о шрифтах, которые будут заменены при рендеринге указанных слайдов. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ru/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Добавляет встраиваемый шрифт<br/>            Имейте в виду, что большинство шрифтов защищены авторским правом. Сначала найдите лицензию <br/>            шрифта и убедитесь, что её можно свободно передать на другую машину. Может быть выброшено исключение ArgumentException, если данные шрифта равны None или этот шрифт уже встроен. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ru/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Добавляет встраиваемый шрифт<br/>            Имейте в виду, что большинство шрифтов защищены авторским правом. Сначала найдите лицензию <br/>            шрифта и убедитесь, что её можно свободно передать на другую машину. Может быть выброшено исключение ArgumentException, если данные шрифта равны None или этот шрифт уже встроен. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ru/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Заменить шрифт в презентации |
| [`replace_font(self, subst_rule)`](/slides/python-net/ru/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Заменить шрифт в презентации, используя информацию, предоставленную в [`FontSubstRule`](/slides/python-net/ru/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/ru/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [`FontSubstRule`](/slides/python-net/ru/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/ru/aspose.slides/fontsmanager/get_fonts/#) | Возвращает шрифты, используемые в презентации |
| [`get_embedded_fonts(self)`](/slides/python-net/ru/aspose.slides/fontsmanager/get_embedded_fonts/#) | Возвращает шрифты, встроенные в презентацию |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ru/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Удаляет встроенный шрифт |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ru/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Получает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ru/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Определяет уровень встраивания шрифта из заданного массива байтов и имени шрифта. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)