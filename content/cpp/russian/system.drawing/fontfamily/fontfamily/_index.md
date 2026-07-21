---
title: FontFamily()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый экземпляр класса FontFamily, представляющий семейство шрифтов с указанным именем.
type: docs
weight: 1
url: /ru/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) конструктор

Создает новый экземпляр класса [FontFamily](../) , представляющего семейство шрифтов с указанным именем.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя семейства шрифтов |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) конструктор

Создает новый экземпляр [FontFamily](../) в указанном FontCollection с заданным именем.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя семейства шрифтов |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollection, содержащий этот экземпляр. |

## FontFamily::FontFamily(Text::GenericFontFamilies) конструктор

Создает новый экземпляр [FontFamily](../) из указанного обобщенного семейства шрифтов.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | Значение GenericFontFamilies для создания [FontFamily](../). |

## Смотрите также

* Перечисление [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [FontFamily](../)
* Класс [FontCollection](../../../system.drawing.text/fontcollection/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)