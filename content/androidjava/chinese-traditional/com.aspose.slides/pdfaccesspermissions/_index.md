---
title: PdfAccessPermissions
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 包含一組旗標，用於指定在使用者開啟文件時應授予哪些存取權限。
type: docs
url: /zh-hant/com.aspose.slides/pdfaccesspermissions/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

包含一組旗標，用於指定在使用者開啟文件時應授予哪些存取權限。
## 欄位

| 欄位 | 說明 |
| --- | --- |
| [None](#None) | 指定使用者沒有存取權限。 |
| [PrintDocument](#PrintDocument) | 指定使用者是否可以列印文件（可能未達最高品質，視位元 [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) 是否也被設定而定）。 |
| [ModifyContent](#ModifyContent) | 指定使用者是否可以透過非由位元 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)、[FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)、[AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) 所控制的操作來修改文件內容。 |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | 指定使用者是否可以透過非位元 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) 所控制的操作複製或以其他方式擷取文件中的文字與圖形。 |
| [AddOrModifyFields](#AddOrModifyFields) | 指定使用者是否可以新增或修改文字註解、填寫互動式表單欄位，且若位元 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 亦被設定，則可以建立或修改互動式表單欄位（包括簽章欄位）。 |
| [FillExistingFields](#FillExistingFields) | 指定使用者是否可以填寫現有的互動式表單欄位（包括簽章欄位），即使位元 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) 為未設定狀態。 |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | 指定使用者是否可以擷取文字與圖形，以支援對有障礙的使用者的可及性或其他用途。 |
| [AssembleDocument](#AssembleDocument) | 指定使用者是否可以組合文件（插入、旋轉或刪除頁面，並建立書籤或縮圖），即使位元 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 為未設定。 |
| [HighQualityPrint](#HighQualityPrint) | 指定使用者是否可以將文件列印成可產生 PDF 內容忠實數位副本的表示形式。 |
### None {#None}
```
public static final int None
```


指定使用者沒有存取權限。

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


指定使用者是否可以列印文件（可能未達最高品質，視位元 [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) 是否也被設定而定）。

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


指定使用者是否可以透過非由位元 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)、[FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields)、[AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) 所控制的操作來修改文件內容。

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


指定使用者是否可以透過非位元 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) 所控制的操作複製或以其他方式擷取文件中的文字與圖形。

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


指定使用者是否可以新增或修改文字註解、填寫互動式表單欄位，且若位元 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 亦被設定，則可以建立或修改互動式表單欄位（包括簽章欄位）。

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


指定使用者是否可以填寫現有的互動式表單欄位（包括簽章欄位），即使位元 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) 為未設定。

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


指定使用者是否可以擷取文字與圖形，以支援對有障礙的使用者的可及性或其他用途。

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


指定使用者是否可以組合文件（插入、旋轉或刪除頁面，並建立書籤或縮圖），即使位元 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 為未設定。

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


指定使用者是否可以將文件列印成可產生 PDF 內容忠實數位副本的表示形式。當此位元未設定（且位元 [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) 已設定）時，列印將受限於外觀的低階表示，可能品質受降級。