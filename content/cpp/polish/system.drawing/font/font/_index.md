---
title: Font()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową instancję klasy Font, która reprezentuje określoną istniejącą czcionkę z podanym stylem czcionki.
type: docs
weight: 1
url: /pl/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor

Tworzy nową instancję klasy [Font](../), która reprezentuje określoną istniejącą czcionkę o podanym stylu czcionki.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Istniejąca czcionka, z której ma zostać utworzona nowa |
| new_style | [FontStyle](../../fontstyle/) | Styl czcionki do zastosowania w nowej czcionce |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Tworzy nową instancję klasy [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Rodzina czcionek nowej czcionki |
| em_size | **float** | Rozmiar em nowej czcionki w jednostkach podanych w parametrze **unit** |
| style | [FontStyle](../../fontstyle/) | Styl nowej czcionki |
| unit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary nowej czcionki |
| gdi_charset | **uint8_t** | Zestaw znaków GDI używany w nowej czcionce |
| gdi_vertical_font | **bool** | Prawda, jeśli nowa czcionka jest pochodną pionowej czcionki GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor

Tworzy nową instancję klasy [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Rodzina czcionek nowej czcionki |
| em_size | **float** | Rozmiar em nowej czcionki w jednostkach podanych w parametrze **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary nowej czcionki |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Tworzy nową instancję klasy [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Nazwa rodziny czcionek nowej czcionki |
| em_size | **float** | Rozmiar em nowej czcionki w jednostkach podanych w parametrze **unit** |
| style | [FontStyle](../../fontstyle/) | Styl nowej czcionki |
| unit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary nowej czcionki |
| gdi_charset | **uint8_t** | Zestaw znaków GDI używany w nowej czcionce |
| gdi_vertical_font | **bool** | Prawda, jeśli nowa czcionka jest pochodną pionowej czcionki GDI |

## Font::Font(const String\&, float, GraphicsUnit) constructor

Tworzy nową instancję klasy [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Nazwa rodziny czcionek nowej czcionki |
| em_size | **float** | Rozmiar em nowej czcionki w jednostkach podanych w parametrze **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Jednostki miary nowej czcionki |

## Zobacz także

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)