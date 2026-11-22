---
title: IFontsManager class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ifontsmanager/
---
## IFontsManager класс

Управляет шрифтами в презентации.

Тип IFontsManager раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/ru/aspose.slides/ifontsmanager/font_subst_rule_list/) | Замены шрифтов, используемые при отображении<br/>            Чтение/запись [`IFontSubstRuleCollection`](/slides/python-net/ru/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/ru/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Представляет коллекцию правил FontFallBack пользователя для управления наборами шрифтов с целью правильных замен с помощью функции резервного шрифта<br/>            Чтение/запись [`IFontFallBackRulesCollection`](/slides/python-net/ru/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/ru/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Указывает, следует ли отдавать предпочтение зарегистрированным шрифтам над встроенными шрифтами с тем же именем и стилем.<br/>            При включении совпадающие встроенные шрифты временно заменяются соответствующими зарегистрированными шрифтами во время экспорта. |

## Методы

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/ru/aspose.slides/ifontsmanager/get_substitutions/#) | Получает информацию о шрифтах, которые будут заменены при отображении презентации. |
| [`get_substitutions(self, slides)`](/slides/python-net/ru/aspose.slides/ifontsmanager/get_substitutions/#listint) | Получает информацию о шрифтах, которые будут заменены при отображении указанных слайдов. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ru/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Добавляет встроенный шрифт.<br/>            Имейте в виду, что большинство шрифтов защищены авторским правом. Сначала найдите лицензию шрифта <br/>            и убедитесь, что её можно свободно перенести на другую машину. Может быть выброшено исключение ArgumentException, если данные шрифта равны None или этот шрифт уже встроен |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/ru/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Добавляет встроенный шрифт<br/>            Имейте в виду, что большинство шрифтов защищены авторским правом. Сначала найдите лицензию шрифта <br/>            и убедитесь, что её можно свободно перенести на другую машину. Может быть выброшено исключение ArgumentException, если данные шрифта равны None или этот шрифт уже встроен |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/ru/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Заменить шрифт в презентации |
| [`replace_font(self, subst_rule)`](/slides/python-net/ru/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Заменить шрифт в презентации, используя информацию, предоставленную в [`IFontSubstRule`](/slides/python-net/ru/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/ru/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Заменить шрифт в презентации, используя информацию, предоставленную в коллекции [`IFontSubstRule`](/slides/python-net/ru/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/ru/aspose.slides/ifontsmanager/get_fonts/#) | Возвращает шрифты, используемые в презентации |
| [`get_embedded_fonts(self)`](/slides/python-net/ru/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Возвращает встроенные в презентацию шрифты |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/ru/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Удаляет встроенный шрифт |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/ru/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Получает массив байтов, представляющий данные шрифта для указанного стиля шрифта и данных шрифта. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/ru/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Определяет уровень встраивания шрифта из данного массива байтов и имени шрифта. |


### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)