---
title: PdfAccessPermissions
second_title: Aspose.Slides dla C++ API Reference
description: Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane, gdy dokument zostaje otwarty z dostępem użytkownika.
type: docs
weight: 989
url: /pl/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions enum


Contains a set of flags specifying which access permissions should be granted when the document is opened with user access.

```cpp
enum class PdfAccessPermissions
```

### Values

| Nazwa | Wartość | Opis |
| --- | --- | --- |
| None | 0 | Określa, że użytkownik nie ma uprawnień dostępu. |
| PrintDocument | 4 | Określa, czy użytkownik może drukować dokument (być może nie w najwyższej jakości, w zależności od tego, czy bit [PdfAccessPermissions::HighQualityPrint](./) jest również ustawiony). |
| ModifyContent | 8 | Określa, czy użytkownik może modyfikować zawartość dokumentu przy użyciu operacji innych niż te kontrolowane przez bity [PdfAccessPermissions::AddOrModifyFields](./), [PdfAccessPermissions::FillExistingFields](./), [PdfAccessPermissions::AssembleDocument](./). |
| CopyTextAndGraphics | 16 | Określa, czy użytkownik może kopiować lub w inny sposób wyodrębniać tekst i grafikę z dokumentu przy użyciu operacji innych niż te kontrolowane przez bit [PdfAccessPermissions::ExtractTextAndGraphics](./). |
| AddOrModifyFields | 32 | Określa, czy użytkownik może dodawać lub modyfikować adnotacje tekstowe, wypełniać interaktywne pola formularza oraz, jeśli bit [PdfAccessPermissions::ModifyContent](./) jest również ustawiony, tworzyć lub modyfikować interaktywne pola formularza (w tym pola podpisu). |
| FillExistingFields | 256 | Określa, czy użytkownik może wypełniać istniejące interaktywne pola formularza (w tym pola podpisu), nawet jeśli bit [PdfAccessPermissions::AddOrModifyFields](./) jest wyczyszczony. |
| ExtractTextAndGraphics | 512 | Określa, czy użytkownik może wyodrębniać tekst i grafikę w celu ułatwienia dostępu użytkownikom niepełnosprawnym lub w innych celach. |
| AssembleDocument | 1024 | Określa, czy użytkownik może zestawiać dokument (wstawiać, obracać lub usuwać strony oraz tworzyć zakładki lub miniatury), nawet jeśli bit [PdfAccessPermissions::ModifyContent](./) jest wyczyszczony. |
| HighQualityPrint | 2048 | Określa, czy użytkownik może drukować dokument do postaci, z której można wygenerować wierną cyfrową kopię zawartości PDF. Gdy ten bit jest wyczyszczony (a bit [PdfAccessPermissions::PrintDocument](./) jest ustawiony), drukowanie jest ograniczone do niskopoziomowej reprezentacji wyglądu, być może o obniżonej jakości. |

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::Export](../)
* Biblioteka [Aspose.Slides](../../)