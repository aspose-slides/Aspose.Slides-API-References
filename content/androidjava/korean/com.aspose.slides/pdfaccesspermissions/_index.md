---
title: PdfAccessPermissions
second_title: Java API 참조를 통해 Android용 Aspose.Slides
description: 문서가 사용자 접근으로 열릴 때 부여되어야 하는 접근 권한을 지정하는 일련의 플래그를 포함합니다.
type: docs
url: /ko/com.aspose.slides/pdfaccesspermissions/
---
**상속:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

문서를 사용자가 접근할 때 부여되어야 하는 접근 권한을 지정하는 일련의 플래그를 포함합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [None](#None) | 사용자에게 접근 권한이 없음을 지정합니다. |
| [PrintDocument](#PrintDocument) | 사용자가 문서를 인쇄할 수 있는지 지정합니다(가능한 경우 최고 품질이 아닐 수 있으며, [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) 비트가 설정되어 있는지에 따라 달라집니다). |
| [ModifyContent](#ModifyContent) | 사용자가 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) 비트가 제어하는 작업 외의 작업으로 문서 내용을 수정할 수 있는지 지정합니다. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | 사용자가 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) 비트가 제어하는 작업 외의 작업으로 문서에서 텍스트와 그래픽을 복사하거나 추출할 수 있는지 지정합니다. |
| [AddOrModifyFields](#AddOrModifyFields) | 사용자가 텍스트 주석을 추가하거나 수정하고, 대화형 폼 필드를 채우며, [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 비트가 설정된 경우 대화형 폼 필드(서명 필드 포함)를 생성하거나 수정할 수 있는지 지정합니다. |
| [FillExistingFields](#FillExistingFields) | 사용자가 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) 비트가 해제된 경우에도 기존 대화형 폼 필드(서명 필드 포함)를 채울 수 있는지 지정합니다. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | 사용자가 장애인 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출할 수 있는지 지정합니다. |
| [AssembleDocument](#AssembleDocument) | 사용자가 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 비트가 해제된 경우에도 문서를 구성(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성)할 수 있는지 지정합니다. |
| [HighQualityPrint](#HighQualityPrint) | 사용자가 PDF 내용의 정확한 디지털 복사본을 생성할 수 있는 표현으로 문서를 인쇄할 수 있는지 지정합니다. |
### None {#None}
```
public static final int None
```


사용자에게 접근 권한이 없음을 지정합니다.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


사용자가 문서를 인쇄할 수 있는지 지정합니다(가능한 경우 최고 품질이 아닐 수 있으며, [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) 비트가 설정되어 있는지에 따라 달라집니다).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


사용자가 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) 비트가 제어하는 작업 외의 작업으로 문서 내용을 수정할 수 있는지 지정합니다.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


사용자가 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) 비트가 제어하는 작업 외의 작업으로 문서에서 텍스트와 그래픽을 복사하거나 추출할 수 있는지 지정합니다.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


사용자가 텍스트 주석을 추가하거나 수정하고, 대화형 폼 필드를 채우며, [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 비트가 설정된 경우 대화형 폼 필드(서명 필드 포함)를 생성하거나 수정할 수 있는지 지정합니다.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


사용자가 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) 비트가 해제된 경우에도 기존 대화형 폼 필드(서명 필드 포함)를 채울 수 있는지 지정합니다.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


사용자가 장애인 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출할 수 있는지 지정합니다.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


사용자가 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) 비트가 해제된 경우에도 문서를 구성(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성)할 수 있는지 지정합니다.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


사용자가 PDF 내용의 정확한 디지털 복사본을 생성할 수 있는 표현으로 문서를 인쇄할 수 있는지 지정합니다. 이 비트가 해제되고 ([PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) 비트가 설정된 경우) 인쇄는 외관의 낮은 수준 표현으로 제한되며, 품질이 저하될 수 있습니다.