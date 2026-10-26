---
title: SensitivityLabelCollection
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 문서에 적용된 민감도 레이블의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/sensitivitylabelcollection/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

문서에 적용된 민감도 레이블의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 인덱스로 민감도 레이블을 반환합니다. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | 컬렉션의 끝에 민감도 레이블을 추가합니다. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | 컬렉션에 SensitivityLabel을 추가합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에서 민감도 레이블을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 요소를 제거합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
| [getCount()](#getCount--) | 컬렉션의 요소 개수를 반환합니다. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | 컬렉션의 모든 요소를 지정된 배열에 복사합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

인덱스로 민감도 레이블을 반환합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

컬렉션의 끝에 민감도 레이블을 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| id | java.lang.String | 민감도 레이블의 ID. |
| siteId | java.util.UUID | Azure Active Directory(Azure AD) 사이트 식별자. |
| isEnabled | boolean | 민감도 레이블이 활성화되었는지 여부를 나타내는 플래그. |
| methodType | int | 민감도 레이블에 대한 할당 방법. |

**반환값:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

컬렉션에 SensitivityLabel을 추가합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | 컬렉션의 끝에 추가될 SensitivityLabel 객체. |

**반환값:**
int - SensitivityLabel이 추가된 인덱스.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에서 민감도 레이블을 제거합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | int | 삭제해야 할 민감도 레이블의 인덱스. |
### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 요소를 제거합니다.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - 컬렉션을 순회하는 데 사용할 수 있는 System.Collections.Generic.IEnumerator1
### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션의 요소 개수를 반환합니다. 읽기 전용 int .

**반환값:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

컬렉션의 모든 요소를 지정된 배열에 복사합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | 대상 배열. |
| index | int | 대상 배열의 시작 인덱스. |