---
title: Font()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр класса Font, представляющего указанный существующий шрифт с указанным стилем шрифта.
type: docs
weight: 1
url: /ru/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) конструктор

Создаёт новый экземпляр класса [Font](../), представляющего указанный существующий шрифт с указанным стилем шрифта.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Существующий шрифт, из которого будет создан новый |
| new_style | [FontStyle](../../fontstyle/) | Стиль шрифта, который будет применён к новому шрифту |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) конструктор

Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Семейство шрифта нового шрифта |
| em_size | **float** | Размер em нового шрифта в единицах, указанных параметром **unit** |
| style | [FontStyle](../../fontstyle/) | Стиль нового шрифта |
| unit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения нового шрифта |
| gdi_charset | **uint8_t** | Набор символов GDI, который будет использован для нового шрифта |
| gdi_vertical_font | **bool** | True, если новый шрифт получен из вертикального шрифта GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) конструктор

Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Семейство шрифта нового шрифта |
| em_size | **float** | Размер em нового шрифта в единицах, указанных параметром **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения нового шрифта |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) конструктор

Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Имя семейства шрифта нового шрифта |
| em_size | **float** | Размер em нового шрифта в единицах, указанных параметром **unit** |
| style | [FontStyle](../../fontstyle/) | Стиль нового шрифта |
| unit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения нового шрифта |
| gdi_charset | **uint8_t** | Набор символов GDI, который будет использован для нового шрифта |
| gdi_vertical_font | **bool** | True, если новый шрифт получен из вертикального шрифта GDI |

## Font::Font(const String\&, float, GraphicsUnit) конструктор

Создаёт новый экземпляр класса [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Имя семейства шрифта нового шрифта |
| em_size | **float** | Размер em нового шрифта в единицах, указанных параметром **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Единицы измерения нового шрифта |

## Смотрите также

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Font](../)
* Класс [FontFamily](../../fontfamily/)
* Класс [String](../../../system/string/)
* Пространство имён [System::Drawing](../../)
* Library [Aspose.Slides](../../../)