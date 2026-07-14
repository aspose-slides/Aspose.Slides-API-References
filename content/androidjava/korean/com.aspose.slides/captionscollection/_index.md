---
title: CaptionsCollection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 닫힌 자막의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/captionscollection/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

닫힌 자막의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스에 있는 자막을 반환합니다. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | 컬렉션의 끝에 WebVTT 자막을 추가합니다. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 스트림에서 컬렉션의 끝에 WebVTT 자막을 추가합니다. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 컬렉션에서 지정된 자막을 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스에 있는 자막을 제거합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 자막을 제거합니다. |
| [getCount()](#getCount--) | 컬렉션의 요소 수를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

지정된 인덱스에 있는 자막을 반환합니다. 읽기 전용 [ICaptions](../../com.aspose.slides/icaptions).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

컬렉션의 끝에 WebVTT 자막을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| label | java.lang.String | 자막의 레이블입니다. |
| filePath | java.lang.String | WebVTT 파일의 경로입니다. |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions) - 추가된 [ICaptions](../../com.aspose.slides/icaptions) 인스턴스.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

스트림에서 컬렉션의 끝에 WebVTT 자막을 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| label | java.lang.String | 자막의 레이블입니다. |
| stream | java.io.InputStream | WebVTT 형식 데이터가 포함된 입력 스트림입니다. |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions) - 추가된 [ICaptions](../../com.aspose.slides/icaptions) 인스턴스.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

컬렉션에서 지정된 자막을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 제거할 자막입니다. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스에 있는 자막을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 자막의 인덱스입니다. |
### clear() {#clear--}
```
public final void clear()
```

컬렉션에서 모든 자막을 제거합니다.
### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션의 요소 수를 반환합니다. 읽기 전용  int .

**반환:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.