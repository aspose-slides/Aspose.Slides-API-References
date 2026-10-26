---
title: Font()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance de la classe Font qui représente la police existante spécifiée avec le style de police spécifié.
type: docs
weight: 1
url: /fr/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructeur

Construit une nouvelle instance de la classe [Font](../) qui représente la police existante spécifiée avec le style de police spécifié.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | La police existante à partir de laquelle créer la nouvelle |
| new_style | [FontStyle](../../fontstyle/) | Un style de police à appliquer à la nouvelle police |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructeur

Construit une nouvelle instance de la classe [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | La famille de police de la nouvelle police |
| em_size | **float** | La taille em de la nouvelle police dans les unités spécifiées par le paramètre **unit** |
| style | [FontStyle](../../fontstyle/) | Le style de la nouvelle police |
| unit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure de la nouvelle police |
| gdi_charset | **uint8_t** | Un jeu de caractères GDI à utiliser pour la nouvelle police |
| gdi_vertical_font | **bool** | Vrai si la nouvelle police est dérivée d'une police verticale GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructeur

Construit une nouvelle instance de la classe [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | La famille de police de la nouvelle police |
| em_size | **float** | La taille em de la nouvelle police dans les unités spécifiées par le paramètre **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure de la nouvelle police |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructeur

Construit une nouvelle instance de la classe [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Le nom de la famille de police de la nouvelle police |
| em_size | **float** | La taille em de la nouvelle police dans les unités spécifiées par le paramètre **unit** |
| style | [FontStyle](../../fontstyle/) | Le style de la nouvelle police |
| unit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure de la nouvelle police |
| gdi_charset | **uint8_t** | Un jeu de caractères GDI à utiliser pour la nouvelle police |
| gdi_vertical_font | **bool** | Vrai si la nouvelle police est dérivée d'une police verticale GDI |

## Font::Font(const String\&, float, GraphicsUnit) constructeur

Construit une nouvelle instance de la classe [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Le nom de la famille de police de la nouvelle police |
| em_size | **float** | La taille em de la nouvelle police dans les unités spécifiées par le paramètre **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Les unités de mesure de la nouvelle police |

## Voir aussi

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Font](../)
* Classe [FontFamily](../../fontfamily/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Drawing](../../)
* Library [Aspose.Slides](../../../)