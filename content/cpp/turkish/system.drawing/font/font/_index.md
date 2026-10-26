---
title: Font()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen mevcut yazı tipini belirtilen yazı tipi stiliyle temsil eden Font sınıfının yeni bir örneğini oluşturur.
type: docs
weight: 1
url: /tr/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) yapıcı

Yeni bir [Font](../) sınıfı oluşturur ve belirtilen mevcut yazı tipini belirtilen yazı tipi stiliyle temsil eder.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Yeni oluşturulacak mevcut yazı tipi |
| new_style | [FontStyle](../../fontstyle/) | Yeni yazı tipine uygulanacak bir yazı tipi stili |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) yapıcı

Yeni bir [Font](../) sınıfı oluşturur.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Yeni yazı tipinin font ailesi |
| em_size | **float** | Yeni yazı tipinin **unit** parametresiyle belirtilen birimlerdeki em boyutu |
| style | [FontStyle](../../fontstyle/) | Yeni yazı tipinin stili |
| unit | [GraphicsUnit](../../graphicsunit/) | Yeni yazı tipinin ölçüm birimleri |
| gdi_charset | **uint8_t** | Yeni yazı tipinde kullanılacak bir GDI karakter seti |
| gdi_vertical_font | **bool** | Yeni yazı tipi bir GDI dikey yazı tipinden türetilmişse true |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) yapıcı

Yeni bir [Font](../) sınıfı oluşturur.

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Yeni yazı tipinin font ailesi |
| em_size | **float** | Yeni yazı tipinin **unit** parametresiyle belirtilen birimlerdeki em boyutu |
| unit | [GraphicsUnit](../../graphicsunit/) | Yeni yazı tipinin ölçüm birimleri |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) yapıcı

Yeni bir [Font](../) sınıfı oluşturur.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Yeni yazı tipinin font ailesinin adı |
| em_size | **float** | Yeni yazı tipinin **unit** parametresiyle belirtilen birimlerdeki em boyutu |
| style | [FontStyle](../../fontstyle/) | Yeni yazı tipinin stili |
| unit | [GraphicsUnit](../../graphicsunit/) | Yeni yazı tipinin ölçüm birimleri |
| gdi_charset | **uint8_t** | Yeni yazı tipinde kullanılacak bir GDI karakter seti |
| gdi_vertical_font | **bool** | Yeni yazı tipi bir GDI dikey yazı tipinden türetilmişse true |

## Font::Font(const String\&, float, GraphicsUnit) yapıcı

Yeni bir [Font](../) sınıfı oluşturur.

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Yeni fontun font ailesinin adı |
| em_size | **float** | Yeni fontun **unit** parametresiyle belirtilen birimlerdeki em boyutu |
| unit | [GraphicsUnit](../../graphicsunit/) | Yeni fontun ölçüm birimleri |

## İlgili

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)