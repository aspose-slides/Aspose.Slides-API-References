---
title: Font()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância da classe Font que representa a fonte existente especificada com o estilo de fonte especificado.
type: docs
weight: 1
url: /pt/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) construtor


Constrói uma nova instância da classe [Font](../) que representa a fonte existente especificada com o estilo de fonte especificado.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | A fonte existente da qual criar a nova |
| new_style | [FontStyle](../../fontstyle/) | Um estilo de fonte a ser aplicado à nova fonte |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) construtor


Constrói uma nova instância da classe [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | A família de fontes da nova fonte |
| em_size | **float** | O tamanho em em da nova fonte nas unidades especificadas pelo parâmetro **unit** |
| style | [FontStyle](../../fontstyle/) | O estilo da nova fonte |
| unit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida da nova fonte |
| gdi_charset | **uint8_t** | Um conjunto de caracteres GDI a ser usado para a nova fonte |
| gdi_vertical_font | **bool** | Verdadeiro se a nova fonte for derivada de uma fonte vertical GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) construtor


Constrói uma nova instância da classe [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | A família de fontes da nova fonte |
| em_size | **float** | O tamanho em em da nova fonte nas unidades especificadas pelo parâmetro **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida da nova fonte |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) construtor


Constrói uma nova instância da classe [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | O nome da família de fontes da nova fonte |
| em_size | **float** | O tamanho em em da nova fonte nas unidades especificadas pelo parâmetro **unit** |
| style | [FontStyle](../../fontstyle/) | O estilo da nova fonte |
| unit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida da nova fonte |
| gdi_charset | **uint8_t** | Um conjunto de caracteres GDI a ser usado para a nova fonte |
| gdi_vertical_font | **bool** | Verdadeiro se a nova fonte for derivada de uma fonte vertical GDI |

## Font::Font(const String\&, float, GraphicsUnit) construtor


Constrói uma nova instância da classe [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | O nome da família de fontes da nova fonte |
| em_size | **float** | O tamanho em em da nova fonte nas unidades especificadas pelo parâmetro **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | As unidades de medida da nova fonte |

## Veja Também

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Font](../)
* Classe [FontFamily](../../fontfamily/)
* Classe [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)