---
title: PdfAccessPermissions
second_title: Aspose.Slides for Java API 레퍼런스
description: 문서를 사용자 액세스로 열었을 때 부여되어야 하는 액세스 권한을 지정하는 플래그 집합을 포함합니다.
type: docs
url: /ko/com.aspose.slides/pdfaccesspermissions/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

문서를 사용자가 열 때 부여되어야 하는 접근 권한을 지정하는 플래그 집합을 포함합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [None](#None) | 사용자가 접근 권한이 없음을 지정합니다. |
| [PrintDocument](#PrintDocument) | 사용자가 문서를 인쇄할 수 있는지 지정합니다(최고 품질이 아닐 수도 있으며, 비트 [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)가 설정되어 있는지에 따라 달라집니다). |
| [ModifyContent](#ModifyContent) | 사용자가 비트 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument)에 의해 제어되는 작업 이외의 작업으로 문서 내용을 수정할 수 있는지 지정합니다. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | 사용자가 비트 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics)에 의해 제어되는 작업 이외의 작업으로 문서에서 텍스트와 그래픽을 복사하거나 추출할 수 있는지 지정합니다. |
| [AddOrModifyFields](#AddOrModifyFields) | 사용자가 텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 채우며, 비트 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent)가 설정된 경우 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정할 수 있는지 지정합니다. |
| [FillExistingFields](#FillExistingFields) | 비트 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)가 해제된 경우에도 사용자가 기존 대화형 양식 필드(서명 필드 포함)를 채울 수 있는지 지정합니다. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | 사용자가 장애가 있는 사용자에 대한 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출할 수 있는지 지정합니다. |
| [AssembleDocument](#AssembleDocument) | 비트 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent)가 해제된 경우에도 사용자가 문서를 조합할 수 있는지 지정합니다(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성). |
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

사용자가 문서를 인쇄할 수 있는지 지정합니다(최고 품질이 아닐 수도 있으며, 비트 [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint)가 설정되어 있는지에 따라 달라집니다).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

사용자가 비트 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument)에 의해 제어되는 작업 이외의 작업으로 문서 내용을 수정할 수 있는지 지정합니다.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

사용자가 비트 [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics)에 의해 제어되는 작업 이외의 작업으로 문서에서 텍스트와 그래픽을 복사하거나 추출할 수 있는지 지정합니다.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

사용자가 텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 채우며, 비트 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent)가 설정된 경우 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정할 수 있는지 지정합니다.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

비트 [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields)가 해제된 경우에도 사용자가 기존 대화형 양식 필드(서명 필드 포함)를 채울 수 있는지 지정합니다.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

사용자가 장애가 있는 사용자에 대한 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출할 수 있는지 지정합니다.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

비트 [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent)가 해제된 경우에도 사용자가 문서를 조합할 수 있는지 지정합니다(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성).

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

사용자가 PDF 내용의 정확한 디지털 복사본을 생성할 수 있는 표현으로 문서를 인쇄할 수 있는지 지정합니다. 이 비트가 해제되고(비트 [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument)가 설정된 경우) 인쇄는 외관의 저수준 표현으로 제한되며, 품질이 저하될 수 있습니다.