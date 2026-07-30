---
title: Font()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří novou instanci třídy Font, která představuje zadaný existující font se zadaným stylem písma.
type: docs
weight: 1
url: /cs/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) konstruktor


Vytvoří novou instanci třídy [Font](../), která představuje zadaný existující font se zadaným stylem písma.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Existující font, ze kterého se vytvoří nový |
| new_style | [FontStyle](../../fontstyle/) | Styl písma, který se použije na nový font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) konstruktor


Vytvoří novou instanci třídy [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Rodina fontu nového fontu |
| em_size | **float** | Velikost em nového fontu v jednotkách specifikovaných parametrem **unit** |
| style | [FontStyle](../../fontstyle/) | Styl nového fontu |
| unit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky nového fontu |
| gdi_charset | **uint8_t** | GDI znaková sada, která se použije pro nový font |
| gdi_vertical_font | **bool** | True pokud je nový font odvozen z vertikálního fontu GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) konstruktor


Vytvoří novou instanci třídy [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Rodina fontu nového fontu |
| em_size | **float** | Velikost em nového fontu v jednotkách specifikovaných parametrem **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky nového fontu |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) konstruktor


Vytvoří novou instanci třídy [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Název rodiny fontu nového fontu |
| em_size | **float** | Velikost em nového fontu v jednotkách specifikovaných parametrem **unit** |
| style | [FontStyle](../../fontstyle/) | Styl nového fontu |
| unit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky nového fontu |
| gdi_charset | **uint8_t** | GDI znaková sada, která se použije pro nový font |
| gdi_vertical_font | **bool** | True pokud je nový font odvozen z vertikálního fontu GDI |

## Font::Font(const String\&, float, GraphicsUnit) konstruktor


Vytvoří novou instanci třídy [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Název rodiny fontu nového fontu |
| em_size | **float** | Velikost em nového fontu v jednotkách specifikovaných parametrem **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Měřicí jednotky nového fontu |

## Viz také

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)