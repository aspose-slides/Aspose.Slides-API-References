---
title: CaptionsCollection
second_title: Aspose.Slides for Java API 레퍼런스
description: 닫힌 캡션의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/captionscollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

닫힌 캡션의 컬렉션을 나타냅니다.

## 메서드

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 닫힌 캡션을 반환합니다. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | WebVTT 닫힌 캡션을 컬렉션의 끝에 추가합니다. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | 스트림에서 WebVTT 닫힌 캡션을 컬렉션의 끝에 추가합니다. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | 지정된 닫힌 캡션을 컬렉션에서 제거합니다. |
| [removeAt(int index)](#removeAt-int-) | 지정된 인덱스의 닫힌 캡션을 제거합니다. |
| [clear()](#clear--) | 컬렉션의 모든 닫힌 캡션을 제거합니다. |
| [getCount()](#getCount--) | 컬렉션의 요소 수를 반환합니다. |
| [iterator()](#iterator--) | 컬렉션을 순회하는 열거자를 반환합니다. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

지정된 인덱스의 닫힌 캡션을 반환합니다. 읽기 전용 [ICaptions](../../com.aspose.slides/icaptions).

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

WebVTT 닫힌 캡션을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| label | java.lang.String | 닫힌 캡션의 레이블. |
| filePath | java.lang.String | WebVTT 파일의 경로. |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions) - 추가된 [ICaptions](../../com.aspose.slides/icaptions) 인스턴스.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

스트림에서 WebVTT 닫힌 캡션을 컬렉션의 끝에 추가합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| label | java.lang.String | 닫힌 캡션의 레이블. |
| stream | java.io.InputStream | WebVTT 형식의 데이터를 포함하는 입력 스트림. |

**반환:**
[ICaptions](../../com.aspose.slides/icaptions) - 추가된 [ICaptions](../../com.aspose.slides/icaptions) 인스턴스.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

지정된 닫힌 캡션을 컬렉션에서 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | 제거할 닫힌 캡션. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

지정된 인덱스의 닫힌 캡션을 제거합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | int | 제거할 닫힌 캡션의 인덱스. |

### clear() {#clear--}
```
public final void clear()
```

컬렉션의 모든 닫힌 캡션을 제거합니다.

### getCount() {#getCount--}
```
public final int getCount()
```

컬렉션의 요소 수를 반환합니다. 읽기 전용 int .

**반환:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

컬렉션을 순회하는 열거자를 반환합니다.

**반환:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - 컬렉션을 순회하는 데 사용할 수 있는 System.Collections.Generic.IEnumerator1