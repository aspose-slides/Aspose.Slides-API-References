---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Microsoft Purview Information Protection에서 제공하는 민감도 레이블을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Microsoft Purview Information Protection에서 제공하는 민감도 레이블을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getId()](#getId--) | 민감도 레이블의 ID를 반환하거나 설정합니다. |
| [setId(String value)](#setId-java.lang.String-) | 민감도 레이블의 ID를 반환하거나 설정합니다. |
| [getSiteId()](#getSiteId--) | 민감도 레이블을 설명하는 민감도 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | 민감도 레이블을 설명하는 민감도 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. |
| [isEnabled()](#isEnabled--) | 민감도 레이블이 활성화되어 있는지 여부를 나타냅니다. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | 민감도 레이블이 활성화되어 있는지 여부를 나타냅니다. |
| [isRemoved()](#isRemoved--) | 민감도 레이블이 제거되었는지 여부를 나타냅니다. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | 민감도 레이블이 제거되었는지 여부를 나타냅니다. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | 민감도 레이블에 대한 할당 방법을 반환하거나 설정합니다. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | 민감도 레이블에 대한 할당 방법을 반환하거나 설정합니다. |
| [getContentMarkTypes()](#getContentMarkTypes--) | 파일에 적용해야 하는 콘텐츠 표시 유형 목록을 반환합니다. |
### getId() {#getId--}
```
public abstract String getId()
```

민감도 레이블의 ID를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

민감도 레이블의 ID를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

민감도 레이블을 설명하는 민감도 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. 읽기/쓰기 java.util.UUID.

**반환:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

민감도 레이블을 설명하는 민감도 레이블 정책에 해당하는 Azure Active Directory (Azure AD) 사이트 식별자를 반환하거나 설정합니다. 읽기/쓰기 java.util.UUID.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

민감도 레이블이 활성화되어 있는지 여부를 나타냅니다.

**반환:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

민감도 레이블이 활성화되어 있는지 여부를 나타냅니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

민감도 레이블이 제거되었는지 여부를 나타냅니다.

**반환:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

민감도 레이블이 제거되었는지 여부를 나타냅니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

민감도 레이블에 대한 할당 방법을 반환하거나 설정합니다. 읽기/쓰기 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**반환:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

민감도 레이블에 대한 할당 방법을 반환하거나 설정합니다. 읽기/쓰기 [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

파일에 적용해야 하는 콘텐츠 표시 유형 목록을 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)