---
title: Font()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza della classe Font che rappresenta il font esistente specificato con lo stile di font specificato.
type: docs
weight: 1
url: /it/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor

Costruisce una nuova istanza della classe [Font](../) che rappresenta il font esistente specificato con lo stile di font specificato.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Il font esistente da cui creare il nuovo |
| new_style | [FontStyle](../../fontstyle/) | Uno stile di font da applicare al nuovo font |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Costruisce una nuova istanza della classe [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | La famiglia di font del nuovo font |
| em_size | **float** | La dimensione em del nuovo font nelle unità specificate dal parametro **unit** |
| style | [FontStyle](../../fontstyle/) | Lo stile del nuovo font |
| unit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura del nuovo font |
| gdi_charset | **uint8_t** | Un set di caratteri GDI da utilizzare per il nuovo font |
| gdi_vertical_font | **bool** | True se il nuovo font deriva da un font verticale GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor

Costruisce una nuova istanza della classe [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | La famiglia di font del nuovo font |
| em_size | **float** | La dimensione em del nuovo font nelle unità specificate dal parametro **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura del nuovo font |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor

Costruisce una nuova istanza della classe [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Il nome della famiglia di font del nuovo font |
| em_size | **float** | La dimensione em del nuovo font nelle unità specificate dal parametro **unit** |
| style | [FontStyle](../../fontstyle/) | Lo stile del nuovo font |
| unit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura del nuovo font |
| gdi_charset | **uint8_t** | Un set di caratteri GDI da utilizzare per il nuovo font |
| gdi_vertical_font | **bool** | True se il nuovo font deriva da un font verticale GDI |

## Font::Font(const String\&, float, GraphicsUnit) constructor

Costruisce una nuova istanza della classe [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Il nome della famiglia di font del nuovo font |
| em_size | **float** | La dimensione em del nuovo font nelle unità specificate dal parametro **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Le unità di misura del nuovo font |

## Vedi anche

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Font](../)
* Classe [FontFamily](../../fontfamily/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Drawing](../../)
* Library [Aspose.Slides](../../../)