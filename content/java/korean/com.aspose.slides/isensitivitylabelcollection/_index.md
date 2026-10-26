---
title: ISensitivityLabelCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 문서에 적용된 민감도 레이블의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isensitivitylabelcollection/
---
**구현된 모든 인터페이스:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

문서에 적용된 민감도 레이블의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 민감도 레이블을 반환합니다. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 컬렉션 끝에 민감도 레이블을 추가합니다. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | SensitivityLabel을 컬렉션에 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 민감도 레이블을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [getCount()](#getCount--) | 컬렉션의 모든 요소 수를 가져옵니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

인덱스로 민감도 레이블을 반환합니다. 읽기 전용 [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

컬렉션 끝에 민감도 레이블을 추가합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| id | java.lang.String | 민감도 레이블의 ID. |
| siteId | java.util.UUID | Azure Active Directory(Azure AD) 사이트 식별자. |
| isEnabled | boolean | 민감도 레이블이 활성화되었는지 여부를 나타내는 플래그. |
| methodType | int | 민감도 레이블의 할당 방법. |

**반환값:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

SensitivityLabel을 컬렉션에 추가합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 컬렉션 끝에 추가될 SensitivityLabel 객체. |

**반환값:**
int - SensitivityLabel이 추가된 인덱스.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

지정된 인덱스의 민감도 레이블을 제거합니다.

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int | 삭제될 민감도 레이블의 인덱스. |
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션의 모든 요소를 제거합니다.

### getCount() {#getCount--}
```
public abstract int getCount()
```

컬렉션의 모든 요소 수를 가져옵니다. 읽기 전용  int .

**반환값:**
int