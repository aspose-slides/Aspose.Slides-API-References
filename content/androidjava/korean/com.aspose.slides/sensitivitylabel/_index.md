---
title: SensitivityLabel
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: Microsoft Purview Information Protection의 민감도 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/sensitivitylabel/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Microsoft Purview Information Protection에서 제공하는 민감도 레이블을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getId()](#getId--) | 민감도 레이블의 ID를 반환하거나 설정합니다. |
| [setId(String value)](#setId-java.lang.String-) | 민감도 레이블의 ID를 반환하거나 설정합니다. |
| [getSiteId()](#getSiteId--) | 민감도 레이블을 설명하는 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 민감도 레이블을 설명하는 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. |
| [isEnabled()](#isEnabled--) | 민감도 레이블이 활성화되었는지 표시합니다. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 민감도 레이블이 활성화되었는지 표시합니다. |
| [isRemoved()](#isRemoved--) | 민감도 레이블이 제거되었는지 표시합니다. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 민감도 레이블이 제거되었는지 표시합니다. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 민감도 레이블의 할당 방법을 반환하거나 설정합니다. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 민감도 레이블의 할당 방법을 반환하거나 설정합니다. |
| [getContentMarkTypes()](#getContentMarkTypes--) | 파일에 적용되어야 하는 콘텐츠 마킹 유형 목록을 반환합니다. |
### getId() {#getId--}
```
public final String getId()
```

민감도 레이블의 ID를 반환하거나 설정합니다. 읽기/쓰기 String.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

민감도 레이블의 ID를 반환하거나 설정합니다. 읽기/쓰기 String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

민감도 레이블을 설명하는 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. 읽기/쓰기 java.util.UUID.

**Returns:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

민감도 레이블을 설명하는 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. 읽기/쓰기 java.util.UUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

민감도 레이블이 활성화되었는지 표시합니다.

**Returns:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

민감도 레이블이 활성화되었는지 표시합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

민감도 레이블이 제거되었는지 표시합니다.

**Returns:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

민감도 레이블이 제거되었는지 표시합니다.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

민감도 레이블의 할당 방법을 반환하거나 설정합니다. 읽기/쓰기 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Returns:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

민감도 레이블의 할당 방법을 반환하거나 설정합니다. 읽기/쓰기 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

파일에 적용되어야 하는 콘텐츠 마킹 유형 목록을 반환합니다.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - 콘텐츠 유형 목록 [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)