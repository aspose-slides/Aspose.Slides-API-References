---
title: PdfAccessPermissions
second_title: Aspose.Slides pro Java – referenční příručka API
description: Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena.
type: docs
url: /cs/com.aspose.slides/pdfaccesspermissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena.
## Pole

| Příznak | Popis |
| --- | --- |
| [None](#None) | Určuje, že uživatel nemá žádná přístupová oprávnění. |
| [PrintDocument](#PrintDocument) | Určuje, zda uživatel může dokument vytisknout (případně ne v nejvyšší kvalitě, v závislosti na tom, zda je také nastaven bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)). |
| [ModifyContent](#ModifyContent) | Určuje, zda uživatel může upravit obsah dokumentu operacemi jinými než těmi, které jsou řízeny bity [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Určuje, zda uživatel může kopírovat nebo jinak extrahovat text a grafiku z dokumentu operacemi jinými než řízenými bitem [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Určuje, zda uživatel může přidávat nebo upravovat textové anotace, vyplňovat interaktivní formulářová pole a pokud je také nastaven bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), vytvářet nebo upravovat interaktivní formulářová pole (včetně polí pro podpis). |
| [FillExistingFields](#FillExistingFields) | Určuje, zda uživatel může vyplňovat existující interaktivní formulářová pole (včetně polí pro podpis), i když je bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) vypnutý. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Určuje, zda uživatel může extrahovat text a grafiku za účelem zpřístupnění uživatelům se zdravotním postižením nebo pro jiné účely. |
| [AssembleDocument](#AssembleDocument) | Určuje, zda uživatel může sestavit dokument (vkládat, otáčet nebo mazat stránky a vytvářet záložky nebo náhledové obrázky), i když je bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) vypnutý. |
| [HighQualityPrint](#HighQualityPrint) | Určuje, zda uživatel může dokument vytisknout do podoby, ze které lze vygenerovat věrnou digitální kopii obsahu PDF. |
### None {#None}
```
public static final int None
```

Určuje, že uživatel nemá žádná přístupová oprávnění.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Určuje, zda uživatel může dokument vytisknout (případně ne v nejvyšší kvalitě, v závislosti na tom, zda je také nastaven bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Určuje, zda uživatel může upravit obsah dokumentu operacemi jinými než těmi, které jsou řízeny bity [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Určuje, zda uživatel může kopírovat nebo jinak extrahovat text a grafiku z dokumentu operacemi jinými než řízenými bitem [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Určuje, zda uživatel může přidávat nebo upravovat textové anotace, vyplňovat interaktivní formulářová pole a pokud je také nastaven bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), vytvářet nebo upravovat interaktivní formulářová pole (včetně polí pro podpis).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Určuje, zda uživatel může vyplňovat existující interaktivní formulářová pole (včetně polí pro podpis), i když je bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) vypnutý.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Určuje, zda uživatel může extrahovat text a grafiku za účelem zpřístupnění uživatelům se zdravotním postižením nebo pro jiné účely.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Určuje, zda uživatel může sestavit dokument (vkládat, otáčet nebo mazat stránky a vytvářet záložky nebo náhledové obrázky), i když je bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) vypnutý.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Určuje, zda uživatel může dokument vytisknout do podoby, ze které lze vygenerovat věrnou digitální kopii obsahu PDF. Když je tento bit vypnutý (a bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) je nastaven), tisk je omezen na nízkoúrovňovou reprezentaci vzhledu, možná s nižší kvalitou.