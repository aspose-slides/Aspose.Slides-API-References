---
title: PdfAccessPermissions
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Obsahuje sadu příznaků určujících, jaká přístupová oprávnění mají být při otevření dokumentu uživatelem povolena.
type: docs
url: /cs/com.aspose.slides/pdfaccesspermissions/
---
**Dědičnost:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Obsahuje sadu příznaků určujících, jaká oprávnění k přístupu mají být při otevření dokumentu uživatelem povolena.
## Pole

| Pole | Popis |
| --- | --- |
| [None](#None) | Určuje, že uživatel nemá žádná přístupová oprávnění. |
| [PrintDocument](#PrintDocument) | Určuje, zda uživatel smí tisknout dokument (případně ne v nejvyšší kvalitě, v závislosti na tom, zda je také nastaven bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)). |
| [ModifyContent](#ModifyContent) | Určuje, zda uživatel smí upravovat obsah dokumentu operacemi jinými než těmi, které jsou řízeny bity [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Určuje, zda uživatel smí kopírovat nebo jinak extrahovat text a grafiku z dokumentu operacemi jinými než těmi, které řídí bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Určuje, zda uživatel smí přidávat nebo upravovat textové anotace, vyplňovat interaktivní pole formuláře a, pokud je také nastaven bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), vytvářet nebo upravovat interaktivní pole formuláře (včetně pole podpisu). |
| [FillExistingFields](#FillExistingFields) | Určuje, zda uživatel smí vyplňovat existující interaktivní pole formuláře (včetně pole podpisu), i když je bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) vypnut. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Určuje, zda uživatel smí extrahovat text a grafiku pro podporu přístupnosti uživatelům se zdravotním postižením nebo pro jiné účely. |
| [AssembleDocument](#AssembleDocument) | Určuje, zda uživatel smí sestavit dokument (vkládat, otáčet nebo mazat stránky a vytvářet záložky nebo miniatury), i když je bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) vypnut. |
| [HighQualityPrint](#HighQualityPrint) | Určuje, zda uživatel smí tisknout dokument do podoby, ze které lze vytvořit věrnou digitální kopii obsahu PDF. |

### None {#None}
```
public static final int None
```

Určuje, že uživatel nemá žádná přístupová oprávnění.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Určuje, zda uživatel smí tisknout dokument (případně ne v nejvyšší kvalitě, v závislosti na tom, zda je také nastaven bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Určuje, zda uživatel smí upravovat obsah dokumentu operacemi jinými než těmi, které jsou řízeny bity [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Určuje, zda uživatel smí kopírovat nebo jinak extrahovat text a grafiku z dokumentu operacemi jinými než těmi, které řídí bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Určuje, zda uživatel smí přidávat nebo upravovat textové anotace, vyplňovat interaktivní pole formuláře a, pokud je také nastaven bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent), vytvářet nebo upravovat interaktivní pole formuláře (včetně pole podpisu).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Určuje, zda uživatel smí vyplňovat existující interaktivní pole formuláře (včetně pole podpisu), i když je bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) vypnut.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Určuje, zda uživatel smí extrahovat text a grafiku pro podporu přístupnosti uživatelům se zdravotním postižením nebo pro jiné účely.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Určuje, zda uživatel smí sestavit dokument (vkládat, otáčet nebo mazat stránky a vytvářet záložky nebo miniatury), i když je bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) vypnut.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Určuje, zda uživatel smí tisknout dokument do podoby, ze které lze vytvořit věrnou digitální kopii obsahu PDF. Když je tento bit vypnut (a bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) je nastaven), tisk je omezen na nízkoúrovňovou reprezentaci vzhledu, případně v horší kvalitě.