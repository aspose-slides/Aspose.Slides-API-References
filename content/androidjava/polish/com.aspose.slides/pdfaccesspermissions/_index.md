---
title: PdfAccessPermissions
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane podczas otwierania dokumentu z dostępem użytkownika.
type: docs
url: /pl/com.aspose.slides/pdfaccesspermissions/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Zawiera zestaw flag określających, które uprawnienia dostępu powinny być przyznane podczas otwierania dokumentu z dostępem użytkownika.
## Pola

| Pole | Opis |
| --- | --- |
| [None](#None) | Określa, że użytkownik nie ma uprawnień dostępu. |
| [PrintDocument](#PrintDocument) | Określa, czy użytkownik może drukować dokument (być może nie w najwyższej jakości, w zależności od tego, czy bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) jest również ustawiony). |
| [ModifyContent](#ModifyContent) | Określa, czy użytkownik może modyfikować zawartość dokumentu operacjami innymi niż te kontrolowane przez bity [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Określa, czy użytkownik może kopiować lub w inny sposób wyodrębniać tekst i grafikę z dokumentu operacjami innymi niż te kontrolowane przez bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Określa, czy użytkownik może dodawać lub modyfikować adnotacje tekstowe, wypełniać interaktywne pola formularza oraz, jeśli bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) jest również ustawiony, tworzyć lub modyfikować interaktywne pola formularza (w tym pola podpisu). |
| [FillExistingFields](#FillExistingFields) | Określa, czy użytkownik może wypełniać istniejące interaktywne pola formularza (w tym pola podpisu), nawet jeśli bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) jest wyczyszczony. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Określa, czy użytkownik może wyodrębniać tekst i grafikę w celu zapewnienia dostępności dla użytkowników niepełnosprawnych lub w innych celach. |
| [AssembleDocument](#AssembleDocument) | Określa, czy użytkownik może składać dokument (wstawiać, obracać lub usuwać strony oraz tworzyć zakładki lub miniatury), nawet jeśli bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) jest wyczyszczony. |
| [HighQualityPrint](#HighQualityPrint) | Określa, czy użytkownik może drukować dokument do reprezentacji, z której można wygenerować wierną cyfrową kopię zawartości PDF. |
### None {#None}
```
public static final int None
```

Określa, że użytkownik nie ma uprawnień dostępu.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Określa, czy użytkownik może drukować dokument (być może nie w najwyższej jakości, w zależności od tego, czy bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) jest również ustawiony).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Określa, czy użytkownik może modyfikować zawartość dokumentu operacjami innymi niż te kontrolowane przez bity [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Określa, czy użytkownik może kopiować lub w inny sposób wyodrębniać tekst i grafikę z dokumentu operacjami innymi niż te kontrolowane przez bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Określa, czy użytkownik może dodawać lub modyfikować adnotacje tekstowe, wypełniać interaktywne pola formularza oraz, jeśli bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) jest również ustawiony, tworzyć lub modyfikować interaktywne pola formularza (w tym pola podpisu).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Określa, czy użytkownik może wypełniać istniejące interaktywne pola formularza (w tym pola podpisu), nawet jeśli bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) jest wyczyszczony.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Określa, czy użytkownik może wyodrębniać tekst i grafikę w celu zapewnienia dostępności dla użytkowników niepełnosprawnych lub w innych celach.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Określa, czy użytkownik może składać dokument (wstawiać, obracać lub usuwać strony oraz tworzyć zakładki lub miniatury), nawet jeśli bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) jest wyczyszczony.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Określa, czy użytkownik może drukować dokument do reprezentacji, z której można wygenerować wierną cyfrową kopię zawartości PDF. Gdy ten bit jest wyczyszczony (i bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) jest ustawiony), drukowanie jest ograniczone do niskopoziomowej reprezentacji wyglądu, być może o obniżonej jakości.