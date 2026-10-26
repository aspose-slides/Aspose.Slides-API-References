---
title: Font()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο αντικείμενο της κλάσης Font που αντιπροσωπεύει τη συγκεκριμένη υπάρχουσα γραμματοσειρά με το καθορισμένο στυλ γραμματοσειράς.
type: docs
weight: 1
url: /el/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) constructor


Δημιουργεί ένα νέο αντικείμενο της κλάσης [Font](../) που αντιπροσωπεύει τη συγκεκριμένη υπάρχουσα γραμματοσειρά με το καθορισμένο στυλ γραμματοσειράς.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Η υπάρχουσα γραμματοσειρά από την οποία δημιουργείται η νέα |
| new_style | [FontStyle](../../fontstyle/) | Ένα στυλ γραμματοσειράς που θα εφαρμοστεί στη νέα γραμματοσειρά |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Δημιουργεί ένα νέο αντικείμενο της κλάσης [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Η οικογένεια γραμματοσειρών της νέας γραμματοσειράς |
| em_size | **float** | Το μέγεθος em της νέας γραμματοσειράς στις μονάδες που ορίζονται από την παράμετρο **unit** |
| style | [FontStyle](../../fontstyle/) | Το στυλ της νέας γραμματοσειράς |
| unit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης της νέας γραμματοσειράς |
| gdi_charset | **uint8_t** | Ένα GDI charset που θα χρησιμοποιηθεί για τη νέα γραμματοσειρά |
| gdi_vertical_font | **bool** | True εάν η νέα γραμματοσειρά προέρχεται από μια κάθετη GDI γραμματοσειρά |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) constructor


Δημιουργεί ένα νέο αντικείμενο της κλάσης [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Η οικογένεια γραμματοσειρών της νέας γραμματοσειράς |
| em_size | **float** | Το μέγεθος em της νέας γραμματοσειράς στις μονάδες που ορίζονται από την παράμετρο **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης της νέας γραμματοσειράς |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) constructor


Δημιουργεί ένα νέο αντικείμενο της κλάσης [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Το όνομα της οικογένειας γραμματοσειράς της νέας γραμματοσειράς |
| em_size | **float** | Το μέγεθος em της νέας γραμματοσειράς στις μονάδες που ορίζονται από την παράμετρο **unit** |
| style | [FontStyle](../../fontstyle/) | Το στυλ της νέας γραμματοσειράς |
| unit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης της νέας γραμματοσειράς |
| gdi_charset | **uint8_t** | Ένα GDI charset που θα χρησιμοποιηθεί για τη νέα γραμματοσειρά |
| gdi_vertical_font | **bool** | True εάν η νέα γραμματοσειρά προέρχεται από μια κάθετη GDI γραμματοσειρά |

## Font::Font(const String\&, float, GraphicsUnit) constructor


Δημιουργεί ένα νέο αντικείμενο της κλάσης [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Το όνομα της οικογένειας γραμματοσειράς της νέας γραμματοσειράς |
| em_size | **float** | Το μέγεθος em της νέας γραμματοσειράς στις μονάδες που ορίζονται από την παράμετρο **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης της νέας γραμματοσειράς |

## Δείτε επίσης

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Font](../)
* Κλάση [FontFamily](../../fontfamily/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)